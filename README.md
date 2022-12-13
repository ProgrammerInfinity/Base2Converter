# BinaryConverter

#This is for stings only

message = str(input("Input any word and it will be converted to binary: "))


binary = " ".join(format(ord(c), "b") for c in message)

binary_text = binary
normal = "".join(chr(int(c, 2)) for c in binary_text.split(" "))

print(f'Binary Version: {binary}')

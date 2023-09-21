filename = input("Enter a filename: ")
split_filename = filename.split(".")
if len(split_filename) > 1:
    extension = split_filename[-1]
    if extension == "py":
        print("Python is the extension of this file")
    else:
        print(f"The extension of the file is: {extension}")
else:
    print("The file does not have an extension.")

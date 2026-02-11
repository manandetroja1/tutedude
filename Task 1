# task2.py

def append():
    try:
        # Step 1: Write user input to output.txt
        user_input = input("Enter some data: ")
        with open("output.txt", "w") as file:
            file.write(user_input + "\n")

        # Step 2: Append additional data
        more_data = input("Enter more data to append: ")
        with open("output.txt", "a") as file:
            file.write(more_data + "\n")

        # Step 3: Read and display final content
        print("\nFinal content of 'output.txt':")
        with open("output.txt", "r") as file:
            print(file.read())
    except Exception as e:
        print(f"An error occurred: {e}")

if __name__ == "__main__":
    append()

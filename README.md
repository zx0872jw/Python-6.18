# Python-6.18
def get_num_of_characters(inputStr):
    count = 0
    for i in range(0, len(inputStr)):
        count = count + 1
    return count


if __name__ == '__main__':
    inputStr = input("Enter a sentence or phrase:")
    print('\n\nYou entered:', inputStr)
    print("\nNumber of characters:", get_num_of_characters(inputStr))

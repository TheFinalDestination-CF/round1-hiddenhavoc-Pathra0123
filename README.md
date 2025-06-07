def restore_order(filename):
    with open(filename, "r") as file:
        lines = file.readlines()
# Call function
restore_order("jumbled.txt")

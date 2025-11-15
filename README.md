def split_even_odd(numbers):
    evens = [n for n in numbers if n % 2 == 0]
    odds = [n for n in numbers if n % 2 != 0]
    return evens, odd

if __name__ == "__main__":
    nums = [5, 8, 13, 22, 31, 40]
    evens, odds = split_even_odd(nums)
    print(f"Even numbers: {evens}")
    print(f"Odd numbers: {odds}")

    counter = 0
    for number_one in numbers:
      for number_two in numbers:
        if number_one + number_two == A:
                counter += 1
    return counter/2

pair_sum_count([1,2,3,4,5,6,7], 5)

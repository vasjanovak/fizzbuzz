print('Welcome to the fizzbuzz game')


def game():
	print('')
	try:
		number = int(input('Choose number between 1 and 100'))
		for num in range(number + 1):
			if num % 3 == 0 and num % 5 == 0:
				print('fizzbuzz')
			elif num % 5 == 0:
				print('fizz')
			elif num % 3 == 0:
				print('buzz')
			else:
				print(num)
	except Exception:
		print('Please enter a number!')

	print('')
	one_more_time = input('Would you like to play one more time? Type y/n')
	if one_more_time == 'y':
		game()
	else:
		pass


game()

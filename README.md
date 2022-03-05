- 👋 Hi, I’m @Andre2965
- 👀 I’m interested in everything. 
- 🌱 I’m currently learning.
- 💞️ I’m looking to collaborate in anyway I can.
- 📫 Reach me at afq2de4@gmail.com 

def question():
	answer = input('''can you code?  ''')
	if answer=='yes':
		print('''cool me too''')
	elif answer=='no':
		print('''lol i dont belive you''')
		print(question())
	else:
		print(question())
question()

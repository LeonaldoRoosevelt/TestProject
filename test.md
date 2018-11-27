# TestProject
##This is a test file!
print ("this is test")


>>> urls = [
"http://www.google.com/a.txt",
"http://www.google.com.tw/a.txt",
"http://www.google.com/download/c.jpg",
"http://www.google.co.jp/a.txt",
"http://www.google.com/b.txt",
"https://facebook.com/movie/b.txt",
"http://yahoo.com/123/000/c.jpg",
"http://gliacloud.com/haha.png",
]
>>> url = 'a.txt'
>>> print("a.txt = ", urls.count(url))

>>> urls = "http://www.google.com/a.txt"
>>> print( urls.count("a.txt"))
1
>>> print(urls.count('b.txt'))
0



>>> def sum():
	sum = 0
	for i in range(0, 1000):
		if i%3 == 0 or i%5 == 0:
			sum += i

			
>>> print(sum())
None
>>> def sum():
	sum = 0
	for i in range(0, 1000):
		if i%3 == 0 or i%5 == 0:
			sum += i
	return sum

>>> print(sum())
233168
>>> 

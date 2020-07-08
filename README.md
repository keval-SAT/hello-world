# hello-world
just another repository

"""
python comprehence
"""
#
# ls = []
# for i in range(100):
#     if i%3==0:
#         ls.append(i)
#
# print(ls)
#
# ls = [i for i in range(100) if i%3==0]
# print(ls)
#
# dict1 = {i:f"item{i}" for i in range (1000) if i%2==0 }
# dict2 = {value:key for key,value in dict1.items()}
# print(dict1,dict2)
# print(dict2)
# """
# set ek item one time show"""
# dresses = {"d1","d2","d1","d1","d2"}
# print(dresses)
#
#
# khana = ["roti","karelu","mithu","cheri"]
#
# for item in khana:
#     if item == "roti":
#         print("this is avialble.")
#         break
#
# else:
#     print("your item is not found.")

"""
time caching part"""

#
# import time
# from functools import lru_cache
#
# @lru_cache(maxsize=32)
# def some_work(n):
#     time.sleep(n)
#     return n
#
# if __name__ == '__main__':
#     print("now runnng some work.")
#     some_work(3)
#     some_work(9)
#     some_work(5)
#     some_work(4)
#     print("done.... calling again")
#     some_work(3)
#     print("called again")

"""
else try except finally
"""
#
# f1 = open("kvl.txt")
#
# try:
#     f = open("kevl.txt")
#
# except Exception as e:
#     print(e)
#
# else:
#     print("this will run only if except is not running.")
# finally:
#     print("Run this anyway...")
#     f1.close()
#
# print("imporatn stuff")
"""
corotine """

#
# def searcher():
#     import time
#     # some 4 swcond time consuming task
#     book = "this is a book on harry and code with harry an good"
#     time.sleep(4)
#
#     while True:
#         text = (yield)
#         if text in book:
#             print("your text is in the book")

#         else:
#             print("your text is not in the book")

# search = searcher()
# print("search started")
# next(search)
# search.send("harry")
# input()
# search.send("and")
# search.close()
"""
os modules"""
# import os

# print(dir(os))
# print(os.getcwd())
# # os.chdir("c://")
# # print(os.getcwd())
# print(os.listdir("c://"))
# os.mkdir("this")
# os.mkdir("this/that")
# os.makedirs("kvl/mvl")


# import os
#
# fd = "GFG.txt"
#
# # popen() is similar to open()
# # file = open(fd, 'w')
# # file.write("Hello")
# # file.close()
# file = open(fd, 'r')
# text = file.read()
# print(text)
#
# # popen() provides a pipe/gateway and accesses the file directly
# file = os.popen(fd, 'w')
# file.write("Hello")
# # File not closed, shown in next function
#
# print("hii" , "1000")


# import requests
# print(requests)
#  print(dict)
#
# f = open("kvl.txt" , 'r')
# conant = f.read()
# print(f)
# f.close()
#
# import json
#
# data = '{"var1":"keval" , "var2":56}'
# print(data)
#
# parsed = json.loads(data)
# print(type(parsed))
# print(parsed["var2"])
#
# data2 = { "channel_name":"kvl", "cars": ['RR','rang rover','jaguar'],
#     "collection" : ('car','bangloes'),
#           "isbad":False
# }
# jscomp = json.dumps(data2)
# print(jscomp)

#
# import pickle
# # cars = ["audi" , "BMW" , "Jaguar"]
# # file = "mycar.pkl"
# # fileobj = open(file,'wb')
# # pickle.dump(cars, fileobj)
# # fileobj.close()
#
# file  = "mycar.pkl"
# fileobj = open(file,'rb')
# mycar = pickle.load(fileobj)
# print(mycar)
# print(type(mycar))
# import sklearn
# print(type(sklearn))



# a = int(input("enter the number"))

# def les():
#     for ls in a:
#         if a ==("stop")
#             print("stop")
#             break
#         else:
#             continue

# a = int(input("enter the number"))

# a = 0
# ls = []
# while(True):
#     a = int(input("enter the number"))
#     if a == 22:
#         print("cont")
#         break
#     else:
#         print("dt")
#         continue
# print(ls)














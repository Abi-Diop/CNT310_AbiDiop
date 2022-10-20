#Assignment CNT310 Create Repository
#My last Python Assignment.

words = ["aardvark","cookies","asterisk","cowabunga","gryphon","angular","cringe"]
i = 0
c_counter = 0
while i < len(words):
    if words[i][0] == "c":
        print(words[i])
        c_counter = c_counter + 1
    i += 1
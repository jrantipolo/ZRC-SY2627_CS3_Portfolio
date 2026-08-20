birthYear = int(input("Enter your birth year: "))

def chineseZodiac(birthYear):
    if birthYear < 1900:
        return "Please enter a year after 1900."
    else:
        zodiac = ["Monkey: 猴 (hóu)", "Rooster: 鸡 (jī)", "Dog: 狗 (gǒu)", "Pig: 猪 (zhū)", "Rat: 鼠 (shǔ)", "Ox: 牛 (niú)", 
                  "Tiger: 虎 (hǔ)", "Rabbit: 兔 (tù)", "Dragon: 龙 (lóng)", "Snake: 蛇 (shé)", "Horse: 马 (mǎ)", "Goat: 羊 (yáng)"]
        return "Your chinese zodiac sign is the " + zodiac[birthYear % 12]

print(chineseZodiac(birthYear))

[Output](outputScreenshot.png)

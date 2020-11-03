# tic-tac-toe
CODE OF MY FIRST PROJECT : TIC TAC TOE GAME 
I write it with pycharm :
languge : Puthon



L3 = "        |               |         \nA\u001b[0m       |       B\u001b[0m       |    C\u001b[0m      \n        |               |         \n-------------------------------\n        |               |         \nD\u001b[0m       |       E\u001b[0m       |    F\u001b[0m    \n        |               |         \n-------------------------------\n        |               |        \nG\u001b[0m       |       H\u001b[0m       |    I\u001b[0m    \n        |               |         "


print("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"+L3+ "\n")

def X (A):
    s = input(A)
    if s == "A":
        return  L3.replace(L3[L3.index("A")], ("\u001b[31mX\u001b[0m"))

    elif s == "B":
        return L3.replace(L3[L3.index("B")], ("\u001b[31mX\u001b[0m"))

    elif s == "C":
        return L3.replace(L3[L3.index("C")], ("\u001b[31mX\u001b[0m"))

    elif s == "D":
        return L3.replace(L3[L3.index("D")], ("\u001b[31mX\u001b[0m"))

    elif s == "E":
        return L3.replace(L3[L3.index("E")], ("\u001b[31mX\u001b[0m"))

    elif s == "F":
        return L3.replace(L3[L3.index("F")], ("\u001b[31mX\u001b[0m"))

    elif s == "G":
        return L3.replace(L3[L3.index("G")], ("\u001b[31mX\u001b[0m"))

    elif s == "H":
        return L3.replace(L3[L3.index("H")], ("\u001b[31mX\u001b[0m"))

    elif s == "I":
        return L3.replace(L3[L3.index("I")], ("\u001b[31mX\u001b[0m"))


def O(A):
    s = input(A)
    if s == "A":
        return L3.replace(L3[L3.index("A")], ("\u001b[32mO\u001b[0m"))

    elif s == "B":
        return L3.replace(L3[L3.index("B")], ("\u001b[32mO\u001b[0m"))

    elif s == "C":
        return L3.replace(L3[L3.index("C")], ("\u001b[32mO\u001b[0m"))

    elif s == "D":
        return L3.replace(L3[L3.index("D")], ("\u001b[32mO\u001b[0m"))

    elif s == "E":
        return L3.replace(L3[L3.index("E")], ("\u001b[32mO\u001b[0m"))

    elif s == "F":
        return L3.replace(L3[L3.index("F")], ("\u001b[32mO\u001b[0m"))

    elif s == "G":
        return L3.replace(L3[L3.index("G")], ("\u001b[32mO\u001b[0m"))

    elif s == "H":
        return L3.replace(L3[L3.index("H")], ("\u001b[32mO\u001b[0m"))

    elif s == "I":
        return L3.replace(L3[L3.index("I")], ("\u001b[32mO\u001b[0m"))


L3 = X ("\u001b[32mX=")
print("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"+L3)
L3 = O ("\u001b[32mO=")
print("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"+L3)
L3 = X ("\u001b[32mX=")
print("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"+L3)
L3 = O ("\u001b[32mO=")
print("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"+L3)
L3 = X ("\u001b[32mX=")
print("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"+L3)
L3 = O ("\u001b[32mO=")
print("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"+L3)
L3 = X ("\u001b[32mX=")
print("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"+L3)
L3 = O ("\u001b[32mO=")
print("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"+L3)
L3 = X ("\u001b[32mX=")
print("\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n"+L3

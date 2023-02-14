import turtle

# membuat objek turtle
t = turtle.Turtle()

# mengatur warna pena dan latar belakang
t.pencolor("red")
turtle.bgcolor("white")

# mengatur kecepatan turtle
t.speed(10)

# membuat tulisan "L"
t.left(90)
t.forward(100)
t.right(90)
t.forward(50)

# membuat tulisan "o"
t.penup()
t.goto(60,100)
t.pendown()
t.circle(25)

# membuat tulisan "v"
t.penup()
t.goto(95,100)
t.pendown()
t.left(60)
t.forward(70)
t.right(120)
t.forward(70)

# membuat tulisan "e"
t.penup()
t.goto(145,100)
t.pendown()
t.right(120)
t.forward(50)
t.circle(25,180)
t.forward(50)

# membuat hati
t.penup()
t.goto(30,50)
t.pendown()
t.begin_fill()
t.color('red')
t.left(45)
t.forward(50)
t.circle(35,180)
t.right(90)
t.circle(35,180)
t.forward(50)
t.end_fill()

# menghilangkan turtle
t.hideturtle()

# menahan jendela turtle agar tidak langsung keluar
turtle.done()

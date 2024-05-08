# modul10-timer

<h1>Reflection 1</h1>
<h3>Understanding why</h3>
<br> we can see that the async function runs separately from the main function that starts it. So, "hey hey" might be printed before "howdy!" and "done!" because "hey hey" is outside the async function. This means while the async function is still waiting to finish, the program keeps going and prints "hey hey".</br>

[ss](static/img.png)
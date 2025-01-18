read x
read y

echo -e $((x+y))'\n'$((x-y))'\n'$((x*y))'\n'$((x/y))

------

Output:
Input (stdin)
5
2
Your Output (stdout)
7
3
10
2
Expected Output
7
3
10
2

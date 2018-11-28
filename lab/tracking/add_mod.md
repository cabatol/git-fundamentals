# Question
In a git repository, file `algo.txt` is tracked and unmodified.
Then we do
```
echo "dijkstra" >> algo.txt
git add algo.txt
```

What will happen?
- [ ] Git creates a new blob 
- [ ] Git updates the index file
- [X] Git updates the current working tree

# Explanation

"git add" adds all modified and untracked files into the
current directory  to the stagin area.
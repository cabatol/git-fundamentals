# Question
In a git repository, file `algo.txt` is tracked and unmodified.
Then we do
```
echo "dijkstra" >> algo.txt
git add algo.txt
```

What will happen?
- [x] Git creates a new blob 
- [ ] Git updates the index file
- [ ] Git updates the current working tree

# Explanation
Git creates a new blob, but doesn't put it in the index or update the working tree until a commit is made.
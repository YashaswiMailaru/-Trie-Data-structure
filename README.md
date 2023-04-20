# Trie-Data-structure
Trie is a tree-based data structure, which is used for efficient retrieval of a key in a large dataset of strings.

# Trie
Data structure and relevant algorithms for extremely fast prefix/fuzzy string searching.

Trie is an efficient information retrieval data structure. Using Trie, search complexities can be brought to optimal limit (key length). 

If we store keys in a binary search tree, a well balanced BST will need time proportional to M * log N, where M is the maximum string length and N is the number of keys in the tree.
<hr>

### [Basic Implementation]
<img src="https://github.com/shinchancode/Trie-Data-structure/blob/main/example.png" height="500" />
<hr>

## Usage

Create a Trie with:

```Go
Trie *t = new Trie();
```

Add Keys with:

```Go
// i.e. you could store any information you would like to associate with
// this particular key.
t->insert(word, meaning);
```

Find a key with:

```Go
bool ok = t->search(s);
```

Remove Keys with:

```Go
t->remove(word);
```

Search with:

```Go
t->search(s);
```

Prefix search with:

```Go
t->starts_with(s);
```

Prefix search with recommendations:
```Go
t->show_recommendations(word);
```


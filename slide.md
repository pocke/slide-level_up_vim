class: center, middle

# Level up Vim

## text-object and operator


![vim](vim.svg)

DentooLT #12

http://me.pocke.me/slide-level_up_vim

---


# About me


.col-xs-6[
## Pocke
A web engineer.

- GitHub: [`@pocke`](https://github.com/pocke)
- Twitter [`@p_ck_`](https://twitter.com/p_ck_)
]

.col-xs-6[

.pocke-img[
![pocke](pocke.svg)
]

]



.col-xs-12[
<br>

Follow me! :bow:
]


---


# About me

### Jobs

.center[


[![skyhopper](skyhopper.png)](https://github.com/skyarch-networks/skyhopper)

.sideci-img[
[![sideci](sideci.png)](https://www.sideci.com)
]

]


---

# About me

Salesan Polytechnic

--


.big[
＿人人人人人＿<br>
＞　Dropout　＜<br>
￣Y^Y^Y^Y^Y￣<br>
]






---

# Agenda

1. Tutorial of Vim
  1. What's Vim?
  1. Mode
1. Text-Object and Operator
  1. Basic usage
      1. What's Operator?
      1. What's Text-Object?
  1. Advanced usage (with Plugin)

---


# Questions

1. Do you know Vim?
1. Do you use Vim? 
1. Are you a professional of Vim?






---

class: center, middle

# Tutorial of Vim


---

background-image: url(100million_vim.png)


---


class: center, middle

# What's Vim?

---

# What is Vim?

- Vim is a text editor(or an IDE).
- Vim has some modes(e.g. Insert, Normal and Visual...).
- Vim has Text-Object and Operator!

---

# Vim is a text editor<br>(or an IDE)

.col-xs-6[
- notepad.exe
- Tera pad
- Emacs
- Sublime Text
- Atom
]


.col-xs-6[
- Visual Studio
- Eclipse
- IntelliJ IDEA
]


---

class: center, middle

# Vim has some modes

---


# Vim has some modes

### Insert mode

Type the keyboard, 
the character is entered directly.

Like general editor.

---

# Vim has some modes

### Normal mode

Define many single key shortcuts  
and combination key shortcuts.

---

# Vim has some modes

### Visual mode

TODO

(DEMO)


---


class: center, middle


# Text-Object and Operator

---


class: center, middle


# Basic Usage

---

# Text-Object and Operator

### What's Operator?

Operator is a verb.

### What's Text-Object?

Text-Object is a range.


---

class: center, middle

# What's Operator?


---

# What's Operator?

The Operators are many actions.

- `d` Delete
- `c` Change
- `y` Yank (Copy)
- `v` Visual

See. [:help operator](http://vim-jp.org/vimdoc-ja/motion.html#operator)

---

# What's Operator?


(DEMO)

- When Operator is pressed twice, Operator is applied for a line.


---


class: center, middle

# What's Text-Object?

---

# What's Text-Object?

- Text-Object is composed of two parts.
  1. `i` or `a`
  1. Character(s) for range type


See. [:help text-objects](http://vim-jp.org/vimdoc-ja/motion.html#text-objects)


---

# Diff between a and i

- `a` contains separators(e.g. `()`, `{}`, ...) / whitespace.
- `i` doesn't contains separators/whitespace.


# What's "Char for range type"


`(`, `{`, `[`, and more...


---

class: center, middle

# Advanced Usage<br>with plugin

---

# [terryma/vim-expand-region](https://github.com/terryma/vim-expand-region)


Select Iikanji-ni by Text-Object.


(DEMO)


---


# [kana/vim-textobj-user](https://github.com/kana/vim-textobj-user)

- [rhysd/vim-textobj-ruby](https://github.com/rhysd/vim-textobj-ruby)
- [sgur/vim-textobj-parameter](https://github.com/sgur/vim-textobj-parameter)
- [kana/vim-textobj-entire](https://github.com/kana/vim-textobj-entire)
- [whatyouhide/vim-textobj-xmlattr](https://github.com/whatyouhide/vim-textobj-xmlattr)

---

# [kana/vim-operator-user](https://github.com/kana/vim-operator-user)

- [emonkak/vim-operator-comment](https://github.com/emonkak/vim-operator-comment)
- [tyru/operator-camelize.vim](https://github.com/tyru/operator-camelize.vim)
- [kana/vim-operator-replace](https://github.com/kana/vim-operator-replace)


---

Summary
--------



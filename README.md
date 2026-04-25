# ⚙️ ATC Lab — Automata Theory & Compilers

Lab programs for **Automata Theory and Compilers (ATC)** using Lex and Yacc on Linux.

## 📚 Programs

| Program | Type | Description |
|---------|------|-------------|
| Program 1 | Lex | Lexical analyzer basics |
| Program 2 | Lex | Token recognition |
| Program 3 | Lex | Pattern matching |
| Program 4 | Lex | Advanced patterns |
| Program 5 | Yacc | Simple grammar parser |
| Program 6 | Yacc | Expression grammar |
| Program 7 | Yacc | Statement parser |
| Program 8 | Lex + Yacc | Combined lexer-parser |
| Program 9 | C | Compiler utility |
| Program 10 | Yacc | Complex grammar |

## 🛠️ Tools Required
- `flex` (Lex)
- `bison` (Yacc)
- `gcc`

## 🚀 Running a Lex Program

```bash
lex Program1.l
gcc lex.yy.c -o Program1 -lfl
./Program1
```

## 🚀 Running a Yacc Program

```bash
yacc -d Program5.y
lex Program5.l
gcc lex.yy.c y.tab.c -o Program5 -lfl
./Program5
```

# Gl-ria-
Música litúrgica
\version "2.24.2"
\header {
  title = "Gloria in Excelsis Deo"
  composer = "Inspirado em Marco Frisina"
}

\score {
  \new Staff {
    \tempo 4 = 72
    \key c \major
    \time 4/4

    \relative c' {
      c4 d e2 |
      r4 g a g |
      r4 f e d2 |
      r2 e4 g |
      a2
    }
  }
}

# Operadores `.`, `->` e `::` em Linguagens de Programação Orientadas a Objetos

Este documento apresenta uma **lista extensiva** e um **quadro visual comparativo** dos operadores `.`, `->` e `::` em diversas linguagens de programação, incluindo tanto linguagens populares quanto obscuras, com foco no contexto de orientação a objetos.

---

## ⭐ Lista Extensiva dos Operadores

### 🟢 Operador `.` (ponto)

#### Função Geral:
Usado para **acessar membros (atributos, métodos)** de uma **instância de classe ou estrutura**.

#### Exemplos por linguagem:

| Linguagem       | Uso                                          | Exemplo                          |
|------------------|----------------------------------------------|----------------------------------|
| Java             | Instância e estáticos                       | `obj.metodo()`, `Classe.metodo()`|
| Python           | Tudo é objeto                              | `obj.attr`, `obj.metodo()`       |
| JavaScript       | Propriedades e métodos de objetos           | `obj.nome`, `obj.funcao()`       |
| Ruby             | Acesso a métodos e variáveis               | `objeto.metodo`, `self.metodo`   |
| C#               | Métodos, propriedades, eventos              | `obj.Prop`, `Classe.Metodo()`    |
| C++              | Instância (não ponteiro)                    | `obj.metodo()`                   |
| Swift            | Atributos, métodos, propriedades            | `obj.metodo()`, `obj.valor`      |
| Go               | Structs e interfaces                        | `valor.Metodo()`                 |
| Dart             | Acesso padrão OO                           | `obj.metodo()`, `obj.prop`       |
| TypeScript       | Semelhante ao JavaScript + tipos            | `obj.metodo()`, `obj.attr`       |
| Kotlin           | Igual ao Java                              | `obj.metodo()`                   |
| Nim              | OO baseada em tipos                         | `obj.metodo()`                   |
| Crystal          | OO influenciado por Ruby                    | `obj.metodo()`                   |
| D                | OO e sistemas                               | `obj.metodo()`                   |
| Ring             | OO dinâmica                                 | `obj.metodo()`                   |
| V                | Linguagem moderna baseada em segurança      | `obj.metodo()`                   |
| Zig              | Sem OO tradicional, mas structs têm campos  | `obj.campo`                      |
| OCaml            | OO opcional com objetos                     | `obj#metodo`                     |
| F#               | Suporte parcial a OO                        | `obj.Metodo()`                   |
| Julia            | OO baseado em múltiplos dispatch            | `obj.metodo()`                   |
| Eiffel           | OO puro                                     | `obj.metodo()`                   |
| Ada              | OO com packages e tipos derivados           | `obj.metodo`                     |
| Tcl (OO)         | Com [incr Tcl], objetos acessam métodos     | `$obj method`                    |
| Raku             | OO moderno                                  | `$obj.metodo()`                  |
| Smalltalk        | Tudo é mensagem para objetos                | `obj metodo`                     |
| Object Pascal    | OO estendido do Pascal                      | `obj.Metodo`                     |
| Modula-3         | OO com tipos seguros                        | `obj.metodo()`                   |
| Oberon           | Tipos extensíveis                          | `obj.metodo()`                   |
| Io               | Prototipagem baseada em mensagens           | `obj metodo`                     |
| Rebol            | Dialeto funcional com OO                    | `obj: make object! [...]`        |
| Cobra            | OO com sintaxe expressiva                   | `obj.metodo()`                   |
| Pike             | Suporte forte a OO                         | `obj->metodo()`                  |
| Fantom           | OO para múltiplas VMs                      | `obj.metodo()`                   |
| Red              | OO leve                                    | `obj/metodo` (path notation)     |
| BETA             | OO conceitual com patterns                 | `obj.metodo()`                   |

---

### 🟡 Operador `->` (seta)

#### Função Geral:
Usado para **acessar membros através de ponteiros ou referências**.

#### Exemplos por linguagem:

| Linguagem       | Uso                                         | Exemplo                      |
|------------------|----------------------------------------------|------------------------------|
| C                | `struct` via ponteiro                       | `ptr->campo`                 |
| C++              | Ponteiro OO                                | `ptr->metodo()`              |
| PHP              | Objetos (sem ponteiros reais)              | `$obj->metodo()`             |
| Rust             | Auto-deref (usa `.` mesmo para ponteiros)  | `obj.metodo()`               |
| Go               | Auto-deref (usa `.` mesmo para ponteiros)  | `ptr.Metodo()`               |
| Perl             | Objetos OO                                | `$obj->metodo()`             |
| D                | Ponteiros funcionam como em C++            | `ptr->campo`                 |
| Pike             | Usa `->` para métodos                      | `obj->metodo()`              |

---

### 🔵 Operador `::` (resolução de escopo / referência de método)

#### Função Geral:
1. **Resolução de escopo/namespaces**
2. **Referência de método** (Java/Kotlin)

#### Exemplos por linguagem:

| Linguagem       | Uso                                          | Exemplo                         |
|------------------|----------------------------------------------|---------------------------------|
| C++              | Escopo, membros estáticos                   | `std::cout`, `Classe::func()`   |
| PHP              | Estáticos, constantes, herança               | `Classe::CONSTANTE`             |
| Java             | Referência de método (Java 8+)             | `Math::sqrt`                    |
| Kotlin           | Igual ao Java                              | `String::length`                |
| Rust             | Namespaces, enums                          | `std::io::stdin()`              |
| Perl             | Pacotes e namespaces                       | `Package::Function()`           |
| Scala            | Escopos e objetos                          | `Objeto::funcao`                |
| Haskell          | Qualificação de módulos                    | `Data.List::map`               |
| D                | Membros estáticos e módulos                 | `Modulo::Funcao`                |
| Raku             | Resolução de pacotes                       | `Modulo::Submodulo`            |
| F#               | `::` é operador de cons em listas           | `1 :: [2;3]`                    |
| OCaml            | `::` é operador de cons em listas           | `1 :: [2;3]`                    |

---

## 🧬 Quadro Comparativo de Operadores

### ✅ **Operadores por Linguagem** (amostra ampliada)

| Linguagem       | `.` (instância/estáticos) | `->` (ponteiro ou similar) | `::` (escopo/referência) |
|------------------|---------------------------|-----------------------------|---------------------------|
| Java             | ✅                         | ❌                          | ✅                        |
| C++              | ✅                         | ✅                          | ✅                        |
| Python           | ✅                         | ❌                          | ❌                        |
| PHP              | ✅                         | ✅                          | ✅                        |
| Rust             | ✅                         | ❌ (auto-deref)             | ✅                        |
| Go               | ✅                         | ❌ (auto-deref)             | ❌                        |
| Dart             | ✅                         | ❌                          | ❌                        |
| Ruby             | ✅                         | ❌                          | ❌                        |
| Perl             | ✅                         | ✅                          | ✅                        |
| Swift            | ✅                         | ❌                          | ❌                        |
| Kotlin           | ✅                         | ❌                          | ✅                        |
| Scala            | ✅                         | ❌                          | ✅                        |
| C#               | ✅                         | ❌                          | ❌                        |
| Haskell          | ❌                         | ❌                          | ✅                        |
| TypeScript       | ✅                         | ❌                          | ❌                        |
| F#               | ✅                         | ❌                          | ✅                        |
| Julia            | ✅                         | ❌                          | ❌                        |
| Object Pascal    | ✅                         | ❌                          | ❌                        |
| Eiffel           | ✅                         | ❌                          | ❌                        |
| Ada              | ✅                         | ❌                          | ❌                        |
| Smalltalk        | ✅                         | ❌                          | ❌                        |
| OCaml            | ✅                         | ❌                          | ✅                        |
| Raku             | ✅                         | ❌                          | ✅                        |
| Modula-3         | ✅                         | ❌                          | ❌                        |
| Rebol            | ✅                         | ❌                          | ❌                        |
| Pike             | ✅                         | ✅                          | ❌                        |
| Crystal          | ✅                         | ❌                          | ❌                        |
| D                | ✅                         | ✅                          | ✅                        |
| Io               | ✅                         | ❌                          | ❌                        |
| Ring             | ✅                         | ❌                          | ❌                        |
| Nim              | ✅                         | ❌                          | ❌                        |
| Red              | ✅                         | ❌                          | ❌                        |
| BETA             | ✅                         | ❌                          | ❌                        |
| Oberon           | ✅                         | ❌                          | ❌                        |
| V                | ✅                         | ❌                          | ❌                        |
| Zig              | ✅                         | ❌                          | ❌                        |

---

### 🗂️ Resumo das Funções

| Operador | Uso principal                                 | Destaque                                                   |
|----------|-------------------------------------------------|------------------------------------------------------------|
| `.`      | Acessar **atributos** ou **métodos de instância** | Universal em linguagens OO                                 |
| `->`     | Acesso via **ponteiro ou referência**           | C, C++, PHP, Perl, D, Pike                                 |
| `::`     | **Escopo**, **namespace**, ou **referência**     | C++, PHP, Rust, Java 8+, Kotlin, Scala, Haskell, D, Raku  |

---

Se desejar exportar este Markdown como PDF ou HTML, ou gerar uma imagem da tabela, posso fazer isso também!

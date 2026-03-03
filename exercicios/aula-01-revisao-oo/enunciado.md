# Aula 01 - Exercicios de Revisao de Orientacao a Objetos

**Disciplina:** Programacao II - ECO 2026/1
**Referencia:** https://wilcilene.github.io/estudos/disciplinas/programacaoii-eco/revisao-oo.html

---

## Instrucoes de entrega

1. Dentro da pasta `entregas/`, crie uma pasta com o seu nome (ex.: `entregas/maria-silva/`).
2. Coloque todos os arquivos da sua solucao nessa pasta.
3. Inclua um `README.md` usando o template em `/templates/README-exercicio.md`.
4. Faca commit e abra um Pull Request conforme o `CONTRIBUTING.md`.

---

## Exercicio 1 - Sistema de Biblioteca

Crie as classes:

- `Livro` com `titulo`, `autor`, `ano` e metodo `informacoes()`.
- `UsuarioBiblioteca` com `nome` e lista interna de livros emprestados.
- Metodos: `emprestar(livro)`, `devolver(titulo)`, `listarEmprestimos()`.

Regras:
- Nao permitir emprestar o mesmo livro duas vezes para o mesmo usuario.
- Usar encapsulamento para proteger a lista interna.

---

## Exercicio 2 - Sistema de Pagamentos

Crie uma hierarquia de `Pagamento` com subclasses:

- `PagamentoCartao` (atributos: `numeroCartao`, `nomeTitular`).
- `PagamentoPix` (atributo: `chavePix`).
- `PagamentoBoleto` (atributo: `codigoBarras`).

Cada subclasse sobrescreve o metodo `processar()`.
Crie uma funcao `pagar(pagamento)` que demonstre o polimorfismo.

---

## Exercicio 3 - Refatoracao para OO (desafio opcional)

Pegue um script simples que voce ja tenha em JavaScript e reescreva usando classes.
Descreva no README.md da entrega quais melhorias voce identificou com a refatoracao.

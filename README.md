# iOS Interview Notes

Estou organizando por aqui minhas anotações de estudo para entrevistas técnicas de iOS.

A ideia é revisar assuntos que uso ou já estudei, voltar nos pontos em que ainda tenho dúvidas e escrever com minhas próprias palavras. Alguns textos vão ter exemplos em Swift, outros vão ser só anotações curtas. Não estou tentando montar um guia completo de iOS.

Para os exemplos mais longos, quero usar situações próximas de apps reais, como autenticação, extrato bancário, paginação e navegação.

## Assuntos

| Pasta | O que estou revisando |
| --- | --- |
| `01-swift/` | Linguagem, enums, protocols, generics e ARC |
| `02-memory-management/` | Retain cycles, `weak`, `unowned` e closures |
| `03-concurrency/` | `async/await`, actors, Tasks e cancelamento |
| `04-architecture/` | MVC, MVVM, MVVM-C, SOLID e injeção de dependência |
| `05-uikit/` | ViewCode, Auto Layout, ciclo de vida e listas |
| `06-networking/` | URLSession, HTTP, tratamento de erros e autenticação |
| `07-data-persistence/` | Core Data, SwiftData, Keychain e cache |
| `08-testing/` | XCTest, mocks, stubs e testes assíncronos |
| `09-banking/` | Extrato, Pix, cartões e segurança em apps financeiros |
| `10-system-design/` | Arquitetura de apps, escalabilidade e offline-first |
| `examples/` | Projetos Swift para experimentar os conceitos na prática |

As pastas acima são a organização planejada. Vou adicionando os conteúdos conforme avanço nos estudos.

## Como quero organizar os estudos

Vou separar os assuntos por tema, em vez de guardar listas de perguntas e respostas de entrevistas. Quando um conceito precisar de mais contexto, escrevo um Markdown próprio. Quando o código ficar grande demais para um trecho no texto, deixo um projeto em `examples/`.

Um dos cenários que quero usar é uma tela de extrato bancário com UIKit e MVVM-C. Ela permite revisar responsabilidades entre Service, Repository e ViewModel, além de paginação, cancelamento de Tasks, testes e navegação com Coordinator.

Os exemplos são de estudo. Não devem ser tratados como implementações prontas para produção, principalmente quando envolverem autenticação, dados financeiros ou segurança.

Vou ajustando as anotações conforme encontro erros, testo alternativas ou mudo de ideia sobre alguma solução.

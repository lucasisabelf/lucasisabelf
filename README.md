# Desenvolvedor Back-End e Desktop [<img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="30" />](https://www.linkedin.com/in/lucas-isabel-ferreira/)

Olá! Meu nome é **Lucas Isabel Ferreira Da Silva**. Desenvolvo aplicações **back-end** e **desktop** com foco em problemas que tocam o mundo físico — protocolos seriais, hardware industrial, formatos proprietários, integração com equipamentos que ninguém mais quer tocar.

Tenho experiência sólida com **C#**, criando soluções com **.NET MAUI**, **Blazor**, **WPF** e **WinForms**. No back-end, atuo com **Entity Framework**, **REST APIs**, **JWT**, **gRPC**, **GraphQL** e **event streaming**. Uso **Go** quando o problema exige goroutines e binários leves, e **Python** quando precisa funcionar amanhã.

### Destaques da Minha Jornada

<table>
  <tr>
    <td>
<ul>
  <li>Atuo no desenvolvimento de uma aplicação desktop em <code>WPF</code> integrada a uma <code>API REST ASP.NET MVC</code> de escala global, voltada para o ambiente de manutenção de uma <strong>empresa global de terminais e pinpads de pagamento</strong>.</li>
  <li>Desenvolvi um ecossistema completo de ferramentas para <strong>balanças eletrônicas comerciais SYSTEL</strong> — daemon de sincronização em produção, importadores multi-formato, servidores HTTP com UI embutida, streaming SSE de peso em tempo real via porta serial.</li>
  <li>Implementei <strong>Titan</strong>: uma linguagem de programação com tipagem estática, baseada em Lua, transpiler escrito em Go — porque entender um problema fundo significa às vezes construir a ferramenta que o resolve.</li>
</ul>
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucasisabelf&layout=donut&show_icons=true&theme=transparent" alt="Top Langs" style="width: 200vw">
    </td>
  </tr>
  <tr>
    <td colspan=2>

<div align="center">
  <img src="https://github.com/devicons/devicon/blob/v2.16.0/icons/csharp/csharp-original.svg" title="C#" alt="C#" width="60" height="60"/>
  <img src="https://github.com/devicons/devicon/blob/v2.16.0/icons/blazor/blazor-original.svg" title="Blazor" alt="Blazor" width="60" height="60"/>
  <img src="https://github.com/devicons/devicon/blob/v2.16.0/icons/go/go-original-wordmark.svg" title="GO" alt="GO" width="40" height="60"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="60" height="60"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" title="React Js" alt="React Js" width="60" height="60"/>
  <img src="https://github.com/devicons/devicon/blob/v2.16.0/icons/microsoftsqlserver/microsoftsqlserver-original-wordmark.svg" title="SQL Server" alt="SQL Server" width="60" height="60"/>
  <img src="https://github.com/devicons/devicon/blob/v2.16.0/icons/postgresql/postgresql-original.svg" title="PostgreSQL" alt="PostgreSQL" width="60" height="60"/>
</div>

  </td>
  </tr>
</table>

---

### O que meus projetos têm em comum

O padrão que aparece em quase todo repositório aqui: **o problema é sempre físico**.

Não são apps de gerenciamento genéricas. São ferramentas que precisam falar com uma balança eletrônica pela porta COM3, mandar bytes no formato certo para um roteador WiFi embarcado, imprimir um recibo ESC/POS num papel de 58mm, decodificar um arquivo de texto proprietário com campos de posição fixa que ninguém documentou direito.

Quando o domínio foi entendido, a solução foi reescrita — às vezes em outra linguagem, sempre menor e mais correta. O portfólio inteiro é um registro desse loop.

---

### Projetos

| Projeto | Linguagem | O que é |
|---------|-----------|---------|
| [systel](https://github.com/lucasisabelf/systel) | Python | Daemon de sincronização balança↔PostgreSQL, em produção |
| [EXTRA_SYSTEL](https://github.com/lucasisabelf/EXTRA_SYSTEL) | Python + Go | Sincronizador de dados extras (receitas, nutrição, alergia) |
| [CLIPSE-on-PC](https://github.com/lucasisabelf/CLIPSE-on-PC) | Go | Servidor HTTP com UI embutida para cadastro e envio serial para balança |
| [CLIPSE-PC](https://github.com/lucasisabelf/CLIPSE-PC) | Go | Variante com leitura SSE de peso em tempo real via serial |
| [GBS-MAUI-BLAZOR](https://github.com/lucasisabelf/GBS-MAUI-BLAZOR) | C# / MAUI | Importador multi-formato (MGV/TXITENS/CAD) com interface polimórfica |
| [Importador-NEO---Linux](https://github.com/lucasisabelf/Importador-NEO---Linux) | Go | Importador web com Docker, envia para balanças via FTP |
| [Leitura-Serial-Linux-](https://github.com/lucasisabelf/Leitura-Serial-Linux-) | C# | API que gera recibo ESC/POS com EAN-13 e imprime via `lp` |
| [TSPL-CS](https://github.com/lucasisabelf/TSPL-CS) | C# | CLI para substituição de templates em etiquetas `.prn` e impressão via WinAPI |
| [TaskStream](https://github.com/lucasisabelf/TaskStream) | C# | Backend Kanban com SQLite dinâmico por sala e DI em camadas |
| [Titan](https://github.com/lucasisabelf/Titan) | Go | Linguagem de script com tipagem estática — transpiler + typechecker + runtime |
| [IA-GAME](https://github.com/lucasisabelf/IA-GAME) | Python | Jogo Dino Runner controlado por rede neural Keras em tempo real |
| [DB-KV-GO](https://github.com/lucasisabelf/DB-KV-GO) | Go | KV store in-memory thread-safe com API REST Gin |

---

### Habilidades Secundárias

- Experiência em `Java`, `PHP`, `C++` e `Firebird`
- Sustentação de software e testes de integração
- Criação de **middlewares**, **CLIs** e **ambientes web** integrados
- Suporte N3 remoto e presencial a clientes, revendedores e autorizadas
- Criação e aplicação de treinamentos para autorizadas, redes e clientes finais
- Manutenção de equipamentos e soldagem eletrônica

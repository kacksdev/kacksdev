<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/kacks-workbench-dark.png" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/kacks-workbench-light.png" />
  <img src="./assets/kacks-workbench-light.png" alt="Mesa de produção desenhada a tinta, com documentos de localização, interfaces, código e anotações técnicas" width="100%" />
</picture>

<h1 align="center">KACKS / PROJECTS</h1>

<p align="center">
  <strong>LOCALIZAÇÃO DE JOGOS / ENGENHARIA DE MODS / CONTROLE DE QUALIDADE</strong>
</p>

<p align="center">
  Projetos comunitários em português brasileiro, construídos com contexto, consistência e validação dentro do jogo.
</p>

<p align="center">
  <code>PT-BR</code>&nbsp;&nbsp;
  <code>GACHA</code>&nbsp;&nbsp;
  <code>MODDING</code>&nbsp;&nbsp;
  <code>GRATUITO</code>&nbsp;&nbsp;
  <code>COMUNIDADE</code>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/ink-rule-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/ink-rule-light.svg" />
  <img src="./assets/ink-rule-light.svg" alt="" width="100%" />
</picture>

## 01 / PROJETOS

<table>
  <tr>
    <td width="240" align="center">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="./assets/bd2-icon-dark-v096.jpg" />
        <source media="(prefers-color-scheme: light)" srcset="./assets/bd2-icon-light-v096.jpg" />
        <img src="./assets/bd2-icon-light-v096.jpg" alt="Ícone oficial de Brown Dust 2 reinterpretado em desenho monocromático para o projeto PT-BR" width="210" />
      </picture>
    </td>
    <td>
      <strong><a href="https://github.com/kacksdev/browndust2-ptbr">BROWN DUST 2 PT-BR / PC</a></strong><br />
      Localização comunitária integral de Brown Dust 2 para português brasileiro.<br /><br />
      <code>v0.9.6</code> <code>FASE 4/6</code> <code>VALIDAÇÃO PRIVADA</code><br />
      Compatibilidade: <code>v2.31.8(FHD-046:137)</code><br /><br />
      <strong>223.743</strong> entradas efetivas<br />
      <strong>24.873</strong> entradas com revisão editorial explícita<br />
      <strong>293</strong> títulos musicais preservados<br />
      Auditoria estrutural zerada, Crônicas e Histórias Cotidianas cobertas, crash do guia corrigido e desempenho validado no cliente atual.<br /><br />
      <a href="https://github.com/kacksdev/browndust2-ptbr"><strong>ACOMPANHAR PROGRESSO PÚBLICO →</strong></a>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="145" align="center">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="./assets/nikke-icon-dark.jpg" />
        <source media="(prefers-color-scheme: light)" srcset="./assets/nikke-icon-light.jpg" />
        <img src="./assets/nikke-icon-light.jpg" alt="Ícone de NIKKE reinterpretado em desenho monocromático" width="105" />
      </picture>
    </td>
    <td>
      <strong><a href="https://github.com/kacksdev/nikke-ptbr">NIKKE PT-BR / PC</a></strong><br />
      <code>FASE 0</code> <code>PREPARAÇÃO TÉCNICA</code> <code>SEM BUILD</code><br /><br />
      Mod de localização PT-BR planejado com plugin Unity em runtime, catálogo externo, cobertura de fontes, auditorias estruturais e testes completos dentro do cliente de PC.<br /><br />
      <a href="https://github.com/kacksdev/nikke-ptbr"><strong>ACOMPANHAR PROJETO E FERRAMENTAS →</strong></a>
    </td>
  </tr>
</table>

> Os dois repositórios públicos acompanham o progresso dos mods. Eles não contêm DLLs, catálogos, instaladores nem pacotes jogáveis: no Brown Dust 2 a implementação continua privada; no NIKKE o desenvolvimento ainda está na preparação técnica.

## 02 / ESCOPO DO TRABALHO

| Área | Entrega |
| --- | --- |
| **Localização** | Tradução contextual de narrativa, interface, tutoriais e sistemas, com glossário e terminologia consistentes. |
| **Engenharia** | Extração de conteúdo, integração em runtime, carregamento seguro, instaladores e processos reproduzíveis. |
| **Qualidade** | Auditorias automáticas, revisão editorial, controle de regressões e testes reais dentro do cliente. |
| **Documentação** | Instruções objetivas para instalação, atualização, diagnóstico e remoção do mod. |

## 03 / PROCESSO

<p align="center">
  <code>EXTRAIR</code> →
  <code>MAPEAR</code> →
  <code>LOCALIZAR</code> →
  <code>REVISAR</code> →
  <code>AUDITAR</code> →
  <code>TESTAR</code> →
  <code>EMPACOTAR</code>
</p>

Cada versão precisa manter placeholders, tags, variáveis, quebras funcionais, nomes próprios e elementos de identidade da obra. O trabalho editorial e o trabalho técnico avançam juntos: uma tradução só está pronta quando também funciona corretamente no jogo.

## 04 / FERRAMENTAS

<strong>DESENVOLVIMENTO</strong><br />
<code>C#</code> <code>.NET</code> <code>Python</code> <code>PowerShell</code> <code>Git</code>

<strong>RUNTIME E INTEGRAÇÃO UNITY</strong><br />
<code>Unity</code> <code>BepInEx</code> <code>HarmonyX</code> <code>IL2CPP</code> <code>Il2CppInterop</code> <code>Cpp2IL</code>

<strong>CONTEÚDO E DADOS</strong><br />
<code>JSON</code> <code>CSV</code> <code>YAML</code> <code>Regex</code> <code>AssetRipper</code> <code>UABEA</code> <code>UnityPy</code>

<strong>VALIDAÇÃO</strong><br />
<code>Auditoria estrutural</code> <code>Testes de regressão</code> <code>Hashing</code> <code>Logs</code> <code>QA in-game</code>

> A pilha é validada separadamente em cada jogo. No NIKKE, BepInEx, HarmonyX, AssetRipper, UABEA e UnityPy compõem a arquitetura planejada; Cpp2IL e Il2CppInterop entram somente se o backend confirmado for IL2CPP.

## 05 / PADRÃO DE QUALIDADE

| Regra | Critério |
| --- | --- |
| **Contexto antes da literalidade** | Intenção, personalidade e emoção têm prioridade sobre substituições palavra por palavra. |
| **Consistência verificável** | Glossário, nomes, títulos, pontuação e escolhas recorrentes precisam permanecer uniformes. |
| **Identidade preservada** | Músicas, nomes próprios e termos de marca ficam no original quando traduzi-los prejudicaria a obra. |
| **Integridade técnica** | Nenhuma tradução pode quebrar placeholders, marcações, layout, carregamento ou atualização do cliente. |
| **Publicação responsável** | Uma versão pública exige instalação clara, pacote verificável, documentação e testes suficientes. |

## 06 / AUTORIA E PUBLICAÇÃO

- Projetos comunitários, gratuitos e sem paywall.
- Documentação e progresso públicos desde a preparação de cada mod.
- Implementações, catálogos e pacotes privados até estarem estáveis e prontos para jogadores reais.
- O botão de download dos repositórios públicos entrega somente documentação e imagens enquanto não houver lançamento.
- Sem afiliação oficial com as desenvolvedoras ou publicadoras dos jogos.
- A direção, os testes, o padrão de qualidade e a decisão de publicação permanecem sob minha responsabilidade.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/ink-rule-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/ink-rule-light.svg" />
  <img src="./assets/ink-rule-light.svg" alt="" width="100%" />
</picture>

<p align="center">
  <code>KACKS / COMMUNITY LOCALIZATION / BRASIL</code>
</p>

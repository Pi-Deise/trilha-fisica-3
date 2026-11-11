# trilha-fisica-3

Trilha de aprendizagem de Física III (Eletromagnetismo) com videoaulas animadas em Manim, textos curtos e perguntas comentadas, organizada cena a cena.

# ⚡ Trilha de Aprendizagem: Física III

Bem-vindo(a) à trilha de aprendizagem de **Física III**! Este repositório reúne uma trilha interativa para estudar Eletromagnetismo e todo o código usado para produzir os vídeos. Cada etapa tem um texto curto, um vídeo com uma única cena e perguntas que explicam por que cada alternativa errada está errada.

🔗 **Acesse a trilha:** https://Pi-Deise.github.io/trilha-fisica-3/

---

## 🎯 Objetivos
- Entender os conceitos de carga, força, campo e fluxo elétrico a partir de animações narradas.
- Estudar no próprio ritmo, uma cena por vez.
- Testar o entendimento com perguntas sobre o nome dos fenômenos, a teoria e cálculos, com explicação a cada erro.

---

## 📚 Conteúdo da Trilha

| Guia | Tópico | Vídeos | Questões | Situação |
|:---:|---|:---:|:---:|:---:|
| **1** | Carga Elétrica e Lei de Coulomb | 🎥 13 cenas | 📝 42 | ✅ Disponível |
| **2** | Campo Elétrico | 🎥 14 cenas | 📝 51 | ✅ Disponível |
| **3** | Lei de Gauss: o campo de um fio de cargas | 🎥 9 cenas | 📝 27 | ✅ Disponível |
| **4** | Potencial Elétrico | 🎥 | 📝 | 🛠️ Em breve |

### 🗺️ Próximas guias planejadas
- Capacitância
- Corrente, Resistência e Circuitos DC
- Campo Magnético e Força Magnética
- Indução Eletromagnética e Lei de Faraday

### 🔬 Guia 1 — Lei de Coulomb, cena a cena

| Etapa | Cena | Tema |
|:---:|---|---|
| 1 | `CoulombAbertura` | Atração e repulsão |
| 2 | `CoulombCondutores` | Condutores, isolantes e indução |
| 3 | `CoulombBalanca` | A balança de torção |
| 4 | `CoulombPropriedades` | As três propriedades da força elétrica |
| 5 | `CoulombFormula` | A fórmula e o sinal das cargas |
| 6 | `CoulombVetorial` | A forma vetorial |
| 7 | `CoulombNucleo` | Gravidade versus eletricidade |
| 8 | `CoulombSuperposicao` | Superposição |
| 9 | `CoulombExemplo3D` | Um exemplo no espaço |
| 10 | `CoulombEquilibrio` | Equilíbrio de um próton |
| 11 | `CoulombCascas` | Cascas e esferas condutoras |
| 12 | `CoulombQuantizacao` | Carga quantizada e conservada |
| 13 | `CoulombFechamento` | Revisão e ponte para Gauss |

### 🌐 Guia 2 — Campo Elétrico, cena a cena

| Etapa | Cena | Tema |
|:---:|---|---|
| 1 | `CampoAcaoDistancia` | Ação a distância |
| 2 | `CampoCargaProva` | A carga de prova e E = F/q₀ |
| 3 | `CampoLinhas` | Linhas de campo |
| 4 | `CampoCargaPontual` | O campo de uma carga pontual |
| 5 | `CampoSuperposicao` | Superposição (Exemplo 22.01) |
| 6 | `CampoDipolo` | O dipolo elétrico |
| 7 | `CampoSprites` | Sprites e o dipolo nuvem-terra (Exemplo 22.02) |
| 8 | `CampoAnel` | O anel carregado |
| 9 | `CampoArco` | O arco de 120° (Exemplo 22.03) |
| 10 | `CampoDisco` | O disco e a placa infinita |
| 11 | `CampoForcaCarga` | Uma carga em um campo e a gota de Millikan |
| 12 | `CampoJatoTinta` | Jato de tinta e ruptura dielétrica (Exemplo 22.04) |
| 13 | `CampoDipoloTorque` | O dipolo em um campo (Exemplo 22.05) |
| 14 | `CampoFechamento` | Revisão e ponte para a Lei de Gauss |

### 🧲 Guia 3 — Lei de Gauss, cena a cena

| Etapa | Cena | Tema |
|:---:|---|---|
| 1 | `GaussLinhaCargas` | Uma linha de cargas e a densidade λ |
| 2 | `GaussCampoCargas` | O campo de cada carga e o efeito de borda |
| 3 | `GaussFioInfinito` | Do conjunto de cargas ao fio infinito |
| 4 | `GaussSuperficie` | A superfície gaussiana |
| 5 | `GaussSimetria` | A lei de Gauss e a simetria |
| 6 | `GaussNormais` | Os vetores normais |
| 7 | `GaussFluxoLateral` | Fluxo na lateral |
| 8 | `GaussFluxoTampas` | Fluxo nas tampas |
| 9 | `GaussResultado` | O campo de um fio infinito: E = λ/(2πε₀r) |

---

## 🚀 Como Utilizar (estudantes)
1. Abra a trilha pelo link acima e escolha a guia.
2. Siga as etapas na ordem: cada uma é liberada quando a anterior é concluída.
3. Leia o texto, assista ao vídeo da cena e responda às perguntas.
4. Errou? A explicação mostra por que aquela alternativa está errada; tente outra.
5. Ganhe XP e até 3 estrelas por etapa. Etapas concluídas podem ser revistas ou refeitas.

O progresso fica salvo no navegador do aparelho usado.

---

## 🎬 Como gerar e publicar os vídeos (professores e colaboradores)
Os vídeos são produzidos com [Manim Community](https://www.manim.community/) e narrados com [manim-voiceover](https://github.com/ManimCommunity/manim-voiceover) usando gTTS em português do Brasil.

1. Abra o notebook da guia, na pasta `notebooks/`, no Google Colab.
2. Rode a célula de instalação e as células `%%writefile` (módulos auxiliares).
3. Rode as células das cenas:
   - `-pql --fps 15`: 480p, rápido, bom para testar;
   - `-pqh`: 1080p, para a versão final.
4. Rode a célula final **"Empacotar os vídeos para o GitHub"**. Ela baixa um `.zip` com os vídeos já com os nomes certos. No notebook da Lei de Coulomb, o código dessa célula está em `videos/coulomb/LEIA-ME.txt`.
5. No GitHub, entre na pasta da guia (`videos/coulomb`, `videos/campo` ou `videos/gauss`), clique em **Add file → Upload files**, arraste os `.mp4` e confirme com **Commit changes**.

> ⚠️ O nome de cada vídeo deve ser **exatamente** o nome da cena, com maiúsculas e a extensão `.mp4` (por exemplo, `videos/campo/CampoArco.mp4`). Pelo navegador, cada arquivo pode ter até 25 MB.

---

## 📁 Estrutura do Repositório
```
trilha-fisica-3/
├── index.html                       # a trilha interativa (publicada pelo GitHub Pages)
├── README.md
├── LICENSE
├── notebooks/
│   ├── Lei_de_Coulomb_animacao.ipynb
│   ├── Campos_Eletricos_animacao.ipynb
│   ├── Lei_de_Gauss_cenas.ipynb
│   ├── Lei_de_gauss_fio_de_cargas.ipynb   # versão original da Lei de Gauss, em dois vídeos
│   └── Efeito_Fotoeletrico_animacao.ipynb  # material extra, fora da trilha
└── videos/
    ├── coulomb/                     # CoulombAbertura.mp4, CoulombCondutores.mp4, ...
    ├── campo/                       # CampoAcaoDistancia.mp4, CampoCargaProva.mp4, ...
    └── gauss/                       # GaussLinhaCargas.mp4, GaussCampoCargas.mp4, ...
```

---

## 🛠️ Tecnologias
- **Manim Community** e **manim-voiceover (gTTS)** para as animações narradas.
- **Google Colab** para renderizar sem instalar nada no computador.
- **HTML, CSS e JavaScript** puros na trilha, sem dependências.
- **GitHub Pages** para hospedagem gratuita.

---

## 📖 Referências
- HALLIDAY, D.; RESNICK, R.; WALKER, J. *Fundamentos de Física*, vol. 3: Eletromagnetismo. Cap. 21 (Cargas Elétricas), cap. 22 (Campos Elétricos) e cap. 23 (Lei de Gauss).
- Notas de aula de Física III, seção 1.3: A lei de Coulomb (AUTOR/INSTITUIÇÃO).

Os textos, roteiros e perguntas foram escritos para este projeto, com base nessas obras. Os livros e as notas de aula não estão incluídos no repositório.

---
📌 *Contribuições, correções e sugestões de novas cenas ou perguntas são sempre bem-vindas via Issues e Pull Requests!*

## Licença

- Código (notebooks, scripts e HTML): MIT, ver arquivo LICENSE.
- Conteúdo educacional (vídeos, roteiros, textos e perguntas): CC BY-NC-SA 4.0
  (https://creativecommons.org/licenses/by-nc-sa/4.0/deed.pt-br).

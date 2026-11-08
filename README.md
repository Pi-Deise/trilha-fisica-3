# trilha-fisica-3

Trilha de aprendizagem de Física III (Eletromagnetismo) com videoaulas animadas em Manim, textos curtos e perguntas comentadas, organizada cena a cena.

# ⚡ Trilha de Aprendizagem: Física III

Bem-vindo(a) à trilha de aprendizagem de **Física III**! Este repositório reúne uma trilha interativa para estudar Eletromagnetismo e todo o código usado para produzir os vídeos. Cada etapa da trilha tem um texto curto, um vídeo com uma única cena e perguntas que explicam por que cada alternativa errada está errada.

🔗 **Acesse a trilha:** https://SEU-USUARIO.github.io/trilha-fisica-3/

---

## 🎯 Objetivos
- Entender os conceitos fundamentais da eletrostática a partir de animações narradas.
- Estudar no próprio ritmo, uma cena por vez.
- Testar o entendimento com perguntas sobre o nome dos fenômenos, a teoria e cálculos, recebendo explicação a cada erro.

---

## 📚 Conteúdo da Trilha

| Módulo | Tópico | Vídeos | Questões | Situação |
|---|---|:---:|:---:|:---:|
| **01** | Carga Elétrica e Lei de Coulomb | 🎥 13 cenas | 📝 42 | ✅ Disponível |
| **02** | Lei de Gauss: o campo de um fio de cargas | 🎥 | 📝 | 🛠️ Em preparação |
| **03** | Efeito Fotoelétrico | 🎥 13 cenas | 📝 | 🛠️ Em preparação |

### 🗺️ Próximos módulos planejados
- Potencial Elétrico e Capacitância
- Corrente, Resistência e Circuitos DC
- Campo Magnético e Força Magnética
- Indução Eletromagnética e Lei de Faraday

### 🔬 Módulo 01, cena a cena

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
| 13 | `CoulombFechamento` | Revisão e ponte para a Lei de Gauss |

---

## 🚀 Como Utilizar (estudantes)
1. Abra a trilha pelo link acima e escolha a guia do módulo.
2. Siga as etapas na ordem: cada uma é liberada quando a anterior é concluída.
3. Leia o texto, assista ao vídeo da cena e responda às perguntas.
4. Errou? A explicação mostra por que aquela alternativa está errada; tente outra.
5. Ganhe XP e até 3 estrelas por etapa. Etapas concluídas podem ser revistas ou refeitas.

O progresso fica salvo no navegador do aparelho usado.

---

## 🎬 Como gerar os vídeos (professores e colaboradores)
Os vídeos são produzidos com [Manim Community](https://www.manim.community/) e narrados com [manim-voiceover](https://github.com/ManimCommunity/manim-voiceover) usando gTTS em português do Brasil.

1. Abra o notebook do módulo, na pasta `notebooks/`, no Google Colab.
2. Rode a célula de instalação (LaTeX, FFmpeg, Manim e manim-voiceover).
3. Rode as células `%%writefile`, que gravam os módulos auxiliares.
4. Rode as células das cenas. Cada uma gera um vídeo:
   - `-pql --fps 15`: 480p, rápido, bom para testar;
   - `-pqh`: 1080p, para a versão final.
5. Copie cada vídeo para `videos/<módulo>/` com o nome da cena, por exemplo `videos/coulomb/CoulombAbertura.mp4`.

> No GitHub, cada arquivo pode ter até 100 MB. Os vídeos em 480p têm poucos MB por cena.

---

## 📁 Estrutura do Repositório
```
trilha-fisica-3/
├── index.html                 # a trilha interativa (publicada pelo GitHub Pages)
├── videos/
│   ├── coulomb/               # CoulombAbertura.mp4, CoulombCondutores.mp4, ...
│   ├── gauss/
│   └── fotoeletrico/
├── notebooks/
│   ├── Lei_de_Coulomb_animacao.ipynb
│   ├── Lei_de_gauss_fio_de_cargas.ipynb
│   └── Efeito_Fotoeletrico_animacao.ipynb
├── roteiros/                  # roteiros das animações (fala + ação por trecho)
├── LICENSE
└── README.md
```

---

## 🛠️ Tecnologias
- **Manim Community** e **manim-voiceover (gTTS)** para as animações narradas.
- **Google Colab** para renderizar sem instalar nada no computador.
- **HTML, CSS e JavaScript** puros na trilha, sem dependências.
- **GitHub Pages** para hospedagem gratuita.

---

## 📖 Referências
- HALLIDAY, D.; RESNICK, R.; WALKER, J. *Fundamentos de Física*, vol. 3: Eletromagnetismo, cap. 21 (Cargas Elétricas).
- HALLIDAY, D.; RESNICK, R.; WALKER, J. *Fundamentos de Física*, vol. 4, cap. 38 (Fótons e Ondas de Matéria).
- Notas de aula de Física III, seção 1.3: A lei de Coulomb (AUTOR/INSTITUIÇÃO).

Os textos, roteiros e perguntas foram escritos para este projeto, com base nessas obras. Os livros e as notas de aula não estão incluídos no repositório.

---
📌 *Contribuições, correções e sugestões de novas cenas ou perguntas são sempre bem-vindas via Issues e Pull Requests!*

## Licença

- Código (notebooks, scripts e HTML): MIT, ver arquivo LICENSE.
- Conteúdo educacional (vídeos, roteiros, textos e perguntas): CC BY-NC-SA 4.0
  (https://creativecommons.org/licenses/by-nc-sa/4.0/deed.pt-br).

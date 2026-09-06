# Projeto Alice 3D - Conceitos de Orientação a Objetos

**Universidade Presbiteriana Mackenzie**  
**Curso:** Ciência da Computação  
**Autores:**  
- Renan Dos Santos Jesus (RA: 10748027)  
- [Nome da sua Dupla] (RA: [RA da dupla])  

---

## 1. Storyboard
O storyboard abaixo ilustra a sequência lógica e as cenas principais que guiaram o desenvolvimento da animação.

<img width="1600" height="1017" alt="WhatsApp Image 2026-09-06 at 14 06 23" src="https://github.com/user-attachments/assets/3ac30a9b-915b-4162-ae5c-d624834263c8" />

*   **Resumo da Cena:** Um senhor idoso é abduzido por alienígenas e entra em pânico ao se ver em um ambiente desconhecido. Enquanto os aliens se comunicam em uma língua incompreensível, uma máquina faz o escaneamento do idoso. O clímax cômico ocorre quando a máquina conclui a análise, descobre que abduziram um "HUMANO" por engano, e informa que a busca deve continuar por um "GATO SIAMÊS".

---

## 2. Planejamento da Implementação
A implementação foi dividida mapeando os elementos visuais para conceitos de Orientação a Objetos.

### Classes e Instâncias (Objetos)
Os seguintes objetos foram inseridos no mundo virtual:
*   **Personagens Principais:** 
    *   Classe de Alienígenas: Instâncias `alien` e `alien2`.
    *   Classe de Pessoas (Biped): Instância `elderPerson`.
*   **Adereços (Props) e Cenário:** 
    *   Classe de Máquinas: Instância `espressoMachine` (utilizada de forma criativa como o supercomputador/scanner da nave).
    *   Classe de Formas: Instância `cylinder` (compondo a estrutura do cenário).

### Métodos e Procedimentos
Ações executadas pelos objetos no mundo:
*   **Métodos Nativos:** O método nativo `say` foi amplamente utilizado por todos os objetos (`espressoMachine`, `elderPerson`, `alien` e `alien2`) para criar o diálogo da animação.
*   **Parâmetros de Métodos:** Utilização do parâmetro `duration` dentro do método `say` para controlar o tempo exato em que cada balão de fala fica visível na tela (ex: `duration = 2.0` e `duration = 3.5`), garantindo que o espectador consiga ler a história no ritmo correto.

### Estruturas de Controle
Para orquestrar a animação, utilizamos as seguintes lógicas:
*   **Do in order (Sequência):** A estrutura de controle principal do programa (dentro de `myFirstMethod`). Ela foi fundamental para garantir que o diálogo ocorresse de forma estritamente cronológica, fazendo com que uma fala ou ação só iniciasse após o término completo da fala anterior.

---

## 3. Arquivo do Projeto (Alice)
O código-fonte e os assets da animação estão contidos no arquivo nativo do projeto.

*   **Link para download do `.a3p`:** [Insira o link do Google Drive/OneDrive ou o caminho do arquivo se estiver na mesma pasta do GitHub, ex: `./projeto_final.a3p`]

---

## 4. Explicação dos Conceitos (Vídeo)
Neste vídeo, detalhamos como os conceitos teóricos de Orientação a Objetos (Classes, Objetos, Métodos e Herança) foram aplicados na prática utilizando a ferramenta Alice 3D.

*   **Link para o Vídeo:** [Insira o link do YouTube ou Google Drive]

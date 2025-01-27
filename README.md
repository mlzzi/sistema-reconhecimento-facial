# 🎥 Reconhecimento Facial com Python 🤖

Este repositório contém um projeto de **reconhecimento facial** utilizando Python e várias bibliotecas poderosas para processamento de imagens e detecção de rostos. O objetivo do projeto é identificar e classificar rostos em imagens a partir de URLs públicas, exibindo os resultados com o nome das pessoas detectadas e delimitando os rostos com retângulos verdes.

---

## 🚀 Funcionalidades

- 🖼️ **Baixar Imagens**: A partir de uma URL, o código faz o download da imagem.
- 👤 **Reconhecimento Facial**: Detecta os rostos presentes na imagem.
- 🏷️ **Identificação de Rosto**: Compara os rostos detectados com uma lista de rostos conhecidos, exibindo o nome de quem foi identificado.
- 🖍️ **Exibição de Resultados**: A imagem é exibida com os rostos identificados, com retângulos verdes ao redor de cada rosto.

---

## 🔧 Tecnologias e Bibliotecas Utilizadas

Este projeto faz uso de várias tecnologias modernas e bibliotecas confiáveis para tornar o reconhecimento facial eficiente e acessível:

- **Python** 🐍: Linguagem de programação principal para o desenvolvimento do projeto.
- **OpenCV** 📸: Biblioteca de visão computacional para processamento e manipulação de imagens.
- **face_recognition** 🧠: Biblioteca de reconhecimento facial baseada no poderoso `dlib`.
- **NumPy** ➕: Biblioteca para manipulação eficiente de arrays e operações matemáticas.
- **Matplotlib** 📊: Biblioteca para visualização de imagens e gráficos.
- **Requests** 🌐: Para fazer o download de imagens de URLs de forma simples e eficiente.

---

## 🧠 Como Funciona

O código é estruturado em três funções principais:

1. **`download_image(url)`**: Faz o download da imagem a partir da URL fornecida e a converte para um formato adequado.
2. **`display_image_with_faces(image, face_locations, face_names)`**: Exibe a imagem com os rostos detectados, desenhando retângulos verdes ao redor deles e exibindo os nomes.
3. **`identify_faces_in_image(image_url, known_face_encodings, known_face_names)`**: Identifica e classifica os rostos presentes em uma imagem, comparando-os com os rostos conhecidos. O nome do rosto identificado é exibido ao lado de cada rosto detectado.

---

## 💡 Exemplo de Rosto Conhecido

Este projeto utiliza rostos conhecidos de personagens famosos, incluindo membros do elenco do filme *Interestelar* 👨‍🚀🌌. Aqui estão alguns exemplos: 

- **Jessica Chastain** 🌟  
- **Matthew McConaughey** 🌟  
- **Anne Hathaway** 🌟  
- **Michael Caine** 🌟  

Esses rostos são utilizados para treinar o sistema de reconhecimento, que então tenta identificá-los em imagens fornecidas.

---

✨ **Explore o poder do reconhecimento facial!** ✨

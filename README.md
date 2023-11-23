# Ray-Marching Shader with OpenGL

Projeto para criar efeitos gráficos usando Ray Marching

## 📋 Instalações das dependências (Linux)

### Instalação da lib X11

```
sudo apt-get install doxygen dnf xorg-dev
sudo dnf install libXcursor-devel libXi-devel libXinerama-devel libXrandr-devel
```

### Instalação da lib GLFW (GLFW-3.3.8)

Baixar o pacote [GLFW-3.3.8](https://www.glfw.org/download)

Após baixar, extrair e faça a compilação usando os comandos dentro da pasta ```glfw-3.3.8```

```
cmake -S . -B build
cmake build
cd build
make build
sudo make install
```

Ao finalizar, será exibido no terminal, os locais de instalações das libs e os includes como pode ser visto na imagem abaixo:

![glfw-install](./images/img_1.png)

### Instalação do Assimp (Assimp-5.3.1)

Baixe o Assimp [assimp-5.3.1](https://github.com/assimp/assimp)
após baixar, extrair e faça a sua build

```
cd assimp
cmake CMakeLists.txt 
cmake --build .
```

após fazer a build, copie os arquivos ```.so``` para a pasta ```/usr/local/lib``` e crie um atalho do ```libassimp.so.5``` para a 
pasta principal do projeto clonado

## 🔧 Configuração do CodeBlock

Verifique se a configuração do seu codeblock como segue as imagens a seguir:

![img_2](./images/img_2.png)
![img_3](./images/img_3.png)
![img_4](./images/img_4.png)
![img_5](./images/img_5.png)

Pronto, o Codeblock está configurado

### 🚀 Executando um exemplo (TODO)

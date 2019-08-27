# Instalação biblioteca Cônio

Para instalar a biblioteca siga as instruções

1 - Instale uma das IDEs, recomendo a que o professor indicou, caso queira instalar a IDE Code Blocks o procedimento é o mesmo! 
* [DEV C++](https://sourceforge.net/projects/orwelldevcpp/files/latest/download)
* [Code Blocks](https://www.fosshub.com/Code-Blocks.html?dwl=codeblocks-17.12-setup-nonadmin.exe)

2 - Já com a IDE instalada, verifique o caminho que você instalou, no meu caso o caminho é: ``C:\Program Files (x86)\Dev-Cpp``, mas se você instalou na raiz: ``C:\Dev-Cpp`` não tem problema.

3 - Vá até onde você instalou sua IDE e abra a pasta <b>MinGW64</b>, no meu caso ``C:\Program Files (x86)\Dev-Cpp\MinGW64``. Dentro desta pasta podemos encontrar as pastas <b>includes</b> e <b>lib</b>

4 - Dentro do repositório baixado, tem a pasta <b>conio</b>, copie os arquivos <b>conio.c</b> e <b>conio.h</b> para dentro da pasta <b>includes</b>

5 - Novamente dentro da pasta conio, copie o arquivo <b>libconio.a</b> para dentro da pasta <b>lib</b>

6 - copie o codigo abaixo.

```bash
   #include <stdio.h>
   #include <stdlib.h>
   #include <conio.c>
   
   /* run this program using the console pauser or add your own getch, system("pause") or input loop */
   
   int main(int argc, char *argv[]) {
   	
   	gotoxy(10,10);
   	textcolor(YELLOW);
   	printf("Biblioteca conio instalada\n");
   	system("pause");
   }
```

##### Aluno: Guilherme k. Fagundes - Curso: Sistemas para Internet
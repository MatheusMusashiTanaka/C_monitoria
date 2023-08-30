 C_monitoria

resumo da monitoria sobre C:

## Aula 01


### Bibliotecas:
>[!IMPORTANT]
 >- #include <stdio.h>;
 >- #include <stdlib.h>;
 >- #include <locale.h>;
 >- #include <math.h>;

### Barras

<details>
<summary>Barras:</summary>

- \n = quebra de linha
- \t = parágrafo
- \a = alerta

</details>

### Tipos de Variáveis

<details>
<summary>Tipos de Variáveis:</summary>

- char = %c;
- int = %d;
- long int = %ld;
- float = %f, %2f;
- double = %if;

</details>

### Escaneando
 Como escanear:
 
 - scanf("%d" , variavel),


```ruby
exemplo
#include <stdio.h>
void main() {
    int x = 0;

    printf("numero:");
    scanf("%d", &x);
    int variavel = x+ 9;
    printf("%d", variavel);
}
```

### Tipos de portas logicas

<details>
<summary>Portas</summary>
 
- && = E
- || = OU
- ! = negacao
</details>

### Estruturas de decisao

<details>
<summary>decisoes</summary>
 
- if = se
- else if = e se
- else = caso contrario
</details>

### exemplo de goto

```ruby
#include <stdio.h>

/////variaveis


////////executar

int main(){
    int num = 0;
    int comp = 0;
	printf("Valor do num:");
	scanf("%d",&num);
	loop:
	if (comp < num) {
        printf("\"Hello world\"\n");
        comp = comp + 1;
        goto loop;
}
}
```

 

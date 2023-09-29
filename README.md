# rubricaWPF
## Esempio di programma in linguaggio UML

Dopo aver fatto un rapido ripasso sulla piattaforma di Visual Studio, siamo passati alla strutturazione di una classe:


### 1. Abbiamo assegnato un nome alla classe e ne abbiamo definiti gli attributi


```C#
  internal class Contatto
    {
        private int numero;
        private string nome;
        private string cognome;
    }

```




### 2. Utilizzando le proprierty di C#, incapsuliamo il campo "Numero"


```C#
 internal class Contatto
    {
        private int numero;
        private string nome;
        private string cognome;

        public int Numero { get => numero; set => numero = value; }
        public string Nome { get => nome; set => nome = value; }
        public string Cognome { get => cognome; set => cognome = value; }
    }
}
```



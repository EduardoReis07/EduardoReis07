```java
package br.com.sobremim

import java.dev.Desenvolvedor;
 
public class @EduardoReis07 extends Desenvolvedor{

    private String nome = "Eduardo Reis";
    private String area = "Desenvolvimento de RPAs";
    private String formação = "Técnico em Desenvolvimento de Sistemas";
    private String faculdade = "Estudante de Banco de Dados na Fatec Bauru";
    private String trabalho = "Yank Solutions";
    private String local = "Bauru/SP";

    @Override
    public System desenvolver(Skills habilidades){
        /* ... */
    }
}

public class Skills extends Desenvolvedor{
    
    String[] linguagens = new String[]{ "Java", "Html", "Css", "JavaScript", "Php", "C++" };
    String[] frameworks = new String[]{ "Spring Boot", "NodeJS" };
    String[] IDEs = new String[]{ "IntelliJ", "VS Code", "Netbeans" }
}
```


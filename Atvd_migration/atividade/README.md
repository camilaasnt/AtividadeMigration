## Atividade Migration - Tutorial

- Ative o xampp;
- Crie uma pasta no xamp/htdocs;
- Abra essa pasta no Visual Studio Code;

Instale o laravel no seu projeto com o comando composer global require laravel/installer:

<img width="413" height="211" alt="laravel" src="https://github.com/user-attachments/assets/b3b4b8ed-a72b-4621-87ae-e4edc8e1e034" />

Escolha a opção "none": 

<img width="370" height="221" alt="none" src="https://github.com/user-attachments/assets/6d91a696-5c13-4312-8226-95885db3da85" />

Escolha a opção "mysql" , "yes" e "yes":

<img width="606" height="246" alt="sqlll" src="https://github.com/user-attachments/assets/ee911e70-c27e-496f-915a-573e11268238" />

Agora, vamos partir para a criação das migrações. Com o seguinte comando, você vai gerar a tabela Aluno, ele aparecerá no banco de dados e possibilitará todas as suas modificações.

<img width="599" height="104" alt="makemig" src="https://github.com/user-attachments/assets/4ce0798c-3c0b-4f9a-ae8d-5176936d00ed" />

As tabelas foram criadas em sistema/database/migrations;

<img width="299" height="232" alt="migrations" src="https://github.com/user-attachments/assets/46fe7ae5-07c8-4bb5-b838-64df60232391" />

No arquivo aluno_migration, criaremos agora os campos da tabela e seu tipo de dados:

<img width="499" height="425" alt="aluno" src="https://github.com/user-attachments/assets/9a2ec8a2-28e1-4104-aea7-5fc8f3bffbd0" />

Para salvar essas modificações, execute este código:

<img width="424" height="25" alt="phpartisan" src="https://github.com/user-attachments/assets/c07e4f52-a669-4ad8-8d65-11837971b18f" />

Se entrarmos no phpMyAdmin, poderemos ver a tabela montada:

<img width="424" height="25" alt="phpartisan" src="https://github.com/user-attachments/assets/5d7e51c1-5c7a-41ed-b03f-e23793a7bf83" />
<img width="417" height="181" alt="phpmyadminh" src="https://github.com/user-attachments/assets/c17eb449-82b0-410b-9114-172c9251acd0" />


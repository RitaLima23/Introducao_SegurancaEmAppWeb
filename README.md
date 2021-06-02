# Introducao_SegurancaEmAppWeb
Alguns detalhes sobre a introdução do curso 

#Infográfico - OWASP Top 10
*10 Principais Vulnerabilidades em aplicação Web, segundo a OWASP(Open Web Application Security Project)*

 - 1. Injeção : Falhas de injeção como SQL, NoSQL e OS ocorrem quando dados não confiáveis são enviados a um sistema visando executar comandos não lícitos ou acessar dados sem autorização.
 
 - 2. Autenticação : Os mecanismos de autenticação geralmente são implementados incorretamente, permitindo que invasores comprometam senhas e assumam a identidade de outros usuários temporária ou permanentemente.
 
 - 3. Exposição : Muitos aplicativos WEB e API não protegem corretamente os dados confidenciais, permitindo que os invasores roubem e modifiquem esses dados para realizar fraudes.
 
 - 4. Referências a XML : Muitos processadores XML mal configurados avaliam referencias externas nos documentos. Essas entidades podem ser utilizadas para divulgar arquivos internos usando o manipulador de URI de arquivo permitindo execução de comandos remotos e roubo de informações.
 
 - 5. Acesso ao sistema : Restrições sobre o que os usuários autenticados tem permissão para fazer geralente são aplicados incorretamente. Os invasores exploram tais falhas para acessar funcionalidades e dados não autorizados escalonando os níveis de acesso.
 
 - 6. Configurações Incorretas : Resulta de configurações padrão inseguras na estrutura de ferramentas, bibliotecas e aplicativos utilizados na stack do software.
 
 - 7. XSS Scripts : Ocorrem sempre que um aplicativo inclui dados não confiáveis em uma nova página web sem validação, ou atualiza uma página da web existente por meio de uma API que cria HTML ou JavaScript permitindo a execução de scripts não autorizados pelo navegador.
 
 - 8. Desserialização : A Desserialização insegura leva a execução remota de código, ataques de repetição, injeção e ataques de escalonamento den privilégios.
 
 - 9. Componentes Vulneráveis : Existe uma entrada que possibilita a perca séria de dados ou sequestro de dados e servidores.
 
 - 10. Registro e Monitoramento insuficiente : O registro e monitoramento insuficientes, justamente com a integração ausente ou ineficaz com a resposta a incidentes, permitem que os invasores continuem atacando os sistemas, mantenham a persistencia, façam giro para mais sistemas e violem, extraiam ou destruam dados.

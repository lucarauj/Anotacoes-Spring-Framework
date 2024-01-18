[![NPM](https://img.shields.io/npm/l/react)](https://github.com/lucarauj/Anotacoes-Spring-Framework/blob/main/LICENSE)

<h1 align="center">Anotações Java - Spring</h1>

<p align="center"><img width="400px" src="https://github.com/lucarauj/assets/blob/main/Spring.png" /></p>

<br>

<p align="center">
  <a href="#-a">A</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-b">B</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-c">C</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-d">D</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-e">E</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-f">F</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-g">G</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-i">I</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-j">J</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-l">L</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-m">M</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-n">N</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-o">O</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-p">P</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-q">Q</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-r">R</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-s">S</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-t">T</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-v">V</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-w">W</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

<br>


## 📜 A

- @ActiveProfiles("test"):
>*sobrescreve as propriedades definidas no arquivo application.properties ao executar os testes, usando o perfil "test".*
- @AfterAll:
>*indica que o método será executado depois de todos os testes em uma classe de teste.*
- @AfterEach:
>*indica que o método será executado depois de cada teste em uma classe de teste.*
- @AllArgsConstructor:
>*gera automaticamente um construtor com todos os atributos da classe.*
- @Autowired:
>*delega ao Spring a injeção de dependência e inicialização do objeto.*
- @AutoConfigureMockMvc:
>*injeta o objeto MockMvc no contexto da aplicação para testes de integração.*
- @AutoConfigureJsonTesters:
>*habilita e configura automaticamente os testadores de JSON para os testes.*
- @AssertTrue:
>*indica que o valor booleano que está sendo testado deve ser verdadeiro para que o teste seja considerado bem-sucedido.*

<br>

## 📜 B

- @Bean:
>*indica que o método retorna um objeto gerenciado pelo Spring e que deve ser registrado como um bean.*
- @BeforeAll:
>*indica que o método será executado antes de todos os testes em uma classe de teste.*
- @BeforeEach:
>*indica que o método será executado antes de cada teste em uma classe de teste.*
- @Builder:
>*usada para gerar automaticamente métodos de construção de objetos em classes.*

<br>

## 📜 C

- @Captor:
>*captura argumentos de um método para uso em testes.*
- @Cacheable:
>*permite que o resultado de um método seja armazenado em cache pelo Spring para evitar a execução repetida do método com os mesmos parâmetros.*
- @CircuitBreaker:
>*habilita o padrão de circuit breaker em um método de um aplicativo Spring.*
- @CPF:
>*anotação que valida se um valor numérico passado corresponde a um número de CPF válido.*
- @CollectionTable:
>*usada para mapear uma tabela de coleção em uma entidade.*
- @Column:
>*especifica o mapeamento entre um atributo de entidade básico e a coluna correspondente na tabela de banco de dados.*
- @Component:
>*é um estereótipo genérico para qualquer componente gerenciado pelo Spring.*
- @ComponentScan:
>*instrui o Spring a buscar classes anotadas com @Configuration e outras anotações de componentes em um pacote para registrar e gerenciar beans no contexto de aplicação.*
- @Configuration:
>*indica que a classe é uma classe de configuração do Spring que define beans e configurações adicionais.*
- @ConfigurationProperties:
>*usada para mapear um grupo de propriedades em uma classe.*
- @ConvertGroup(from = Default.class, to = ValidationGroups.{parameter}.class):
>*converte de um "grupo de validação" para outro.*
- @ControllerAdvice:
>*permite manipular exceções globalmente em um aplicativo Spring.*
- @CreatedDate:
>*recurso de auditoria fornecido pelo Spring Data JPA que rastreia a data de criação de uma entidade.*
- @CreationTimestamp:
>*registra automaticamente a data e hora em que uma entidade é criada no banco de dados.*
- @CrossOrigin:
>*permite a comunicação entre domínios para métodos manipuladores de solicitações.*

<br>

## 📜 D

- @Data:
>*gera o código padronizado (getters, setters, toString apropriado, equals e implementações hashCode) para os campos de uma classe.*
- @DataJpaTest:
>*usada para testar uma interface Repository em um ambiente de teste.*
- @DisplayName("String"):
>*usada para fornecer um nome personalizado para a classe de teste ou método de teste.*
- @DeleteMapping:
>*usada para mapear solicitações HTTP DELETE para métodos manipuladores específicos.*
- @DecimalMin:
>*especifica que a propriedade decorada com essa anotação deve ter um valor maior ou igual ao mínimo especificado.*
- @DisplayName():
>*nomeia um teste.*
- @DisableIfEnvironmentVariable():
>*executa o método se as variáveis de ambiente fornecidas forem falsas.*

<br>

## 📜 E

- @EqualsAndHashCode:
>*gera automaticamente os métodos equals e hashCode para os campos do objeto.*
- @Embeddable:
>*especifica que um tipo é incorporável e será gerenciado pela entidade proprietária.*
- @Embedded:
>*especifica que um determinado atributo de entidade representa um tipo incorporável.*
- @EmbeddedId:
>*especifica que o identificador de entidade é um tipo incorporável.*
- @EnableFeignClients:
>*habilita o uso do Feign na aplicação.*
- @EnableCaching:
>*ativa o cache na aplicação.*
- @EnableFeignClients:
>*habilita o processo de criação automática de clientes Feign a partir das interfaces marcadas com @FeignClient.*
- @EnableWebSecurity:
>*habilita recursos de segurança em uma aplicação.*
- @EnableGlobalMethodSecurity:
>*habilita o uso de anotações com regras de segurança.*
- @EnableR2dbcAuditing:
>*configura o mecanismo de auditoria no contexto do Spring para uso com R2DBC.*
- @Enumerated(EnumType.STRING):
>*especifica que a representação de uma enumeração será armazenada como uma String na coluna correspondente na tabela do banco de dados.*
- @ElementCollection:
>*especifica que um campo representa uma coleção de elementos embutidos ou básicos.*
- @ElementCollection(fetch = FetchType.EAGER):
>*especifica que a coleção de elementos embutidos ou básicos deve ser buscada imediatamente.*
- @Entity:
>*especifica que a classe anotada representa uma entidade.*
- @Email:
>*verifica se o valor de um campo possui as características de um endereço de e-mail.*
- @EnableIfEnvironmentVariable():
>*executa o método se as variáveis de ambiente fornecidas forem verdadeiras.*
- @EnableOnOs():
>*executa o método se os parâmetros informados relacionados ao sistema operacional forem verdadeiros.*
- @EnableOnJre():
>*executa o método se os parâmetros informados relacionados à JRE forem verdadeiros.*
- @EnableForJreRange():
>*executa o método se os parâmetros informados relacionados às versões da JRE forem verdadeiros.*
- @EnableEurekaServer:
>*permite que o aplicativo funcione como um servidor de registro para outros serviços.*
- @EnableEurekaClient:
>*permite que o aplicativo se registre em um servidor Eureka e utilize a descoberta de serviços fornecida pelo Eureka.*
- @ExtendWith(MockitoExtension.class):
>*permite o uso do Mockito como uma extensão para o framework de teste, fornecendo recursos adicionais para criação e uso de objetos simulados (mocks) durante os testes.*
- @ExceptionHandler:
>*permite que um método trate uma exceção específica quando ela é lançada.*

<br>

## 📜 F

- @FeignClient:
>*injeta o cliente no contexto do Spring para facilitar a comunicação com serviços HTTP.*
- @FunctionalInterface:
>*usada para indicar que uma interface tem apenas um método abstrato.*
- @Future:
>*define que a variável só pode receber uma data futura.*

<br>

## 📜 G

- @GeneratedValue(GenerationType.AUTO):
>*estratégia padrão para geração de valores de identificador. A JPA escolhe a estratégia mais apropriada com base no banco de dados configurado para a aplicação.*
- @GeneratedValue(GenerationType.SEQUENCE):
>*utiliza uma sequência no banco de dados para gerar os valores dos identificadores. É necessário adicionar a anotação @SequenceGenerator para configurar a sequência.*
- @GeneratedValue(GenerationType.IDENTITY):
>*usada quando o banco de dados suporta colunas autoincrementais, como AUTO_INCREMENT no MySQL ou IDENTITY no SQL Server.*
- @GeneratedValue(GenerationType.UUID):
>*indica que o valor do identificador único da entidade será gerado pelo provedor de persistência usando a estratégia UUID.*
- @GeneratedValue(GenerationType.TABLE):
>*utiliza uma tabela especial no banco de dados para gerar os valores dos identificadores. É necessário adicionar a anotação @TableGenerator para configurar a tabela.*
- @GetMapping:
>*mapeia solicitações HTTP GET para métodos manipuladores específicos.*
- @Getter:
>*cria automaticamente os métodos getter para todos os atributos da classe usando o Lombok.*

<br>

## 📜 I

- @Id:
>*especifica o identificador da entidade. Uma entidade sempre deve ter um atributo identificador.*
- @Inject:
>*usada para solicitar que o contêiner do Spring injete dependências em um campo, construtor ou método de um componente gerenciado pelo Spring.*
- @InjectMocks:
>*cria e injeta instâncias simuladas para serem usadas em testes com o Mockito.*

<br>

## 📜 J

- @JsonAlias:
>*mapeia apelidos alternativos para os campos recebidos em JSON.*
- @JsonFormat(pattern = "dd/MM/yyyy HH:mm"):
>*especifica o formato esperado para a data/hora ao serializar ou desserializar em JSON.*
- @JsonInclude(Include.NON_NULL):
>*inclui apenas as propriedades não nulas ao serializar em JSON.*
- @JsonProperty(access = READ_ONLY):
>*indica que o parâmetro é somente leitura.*
- @JsonIgnore:
>*marca uma propriedade para ser ignorada durante a serialização/desserialização JSON no nível do campo.*
- @JsonIgnoreProperties:
>*marca uma propriedade ou um grupo de propriedades para serem ignoradas durante a serialização/desserialização JSON.*
- @JoinColumn:
>*define o mapeamento físico no lado proprietário em um relacionamento um-para-muitos/muitos-para-um.*
- @JoinTable:
>*define o nome de uma tabela intermediária em um relacionamento muitos-para-muitos.*

<br>

## 📜 L

- @LastModifiedDate:
>*utilizada para rastrear quando a entidade foi modificada pela última vez.*

<br>

## 📜 M

- @Min:
>*usada para aplicar validações de valor mínimo a propriedades de um objeto.*
- @Modifying:
>*informa ao Spring Data que a consulta anotada com @Query é uma operação de escrita (atualização, exclusão, etc.) e não uma consulta de leitura.*
- @Modifying(clearAutomatically = true):
>*indica ao Spring Data JPA que a consulta resultará em uma modificação no banco de dados e que o contexto de persistência deve ser limpo automaticamente após a execução da consulta.*
- @Mock:
>*cria um objeto simulado (mock) usado para testes com o Mockito.*
- @MockBean:
>*cria um objeto simulado (mock) de uma classe ou interface e o adiciona ao contexto de aplicação para uso em testes.*
- @ManyToOne:
>*especifica um relacionamento de banco de dados muitos-para-um.*
- @ManyToMany:
>*especifica um relacionamento de banco de dados muitos-para-muitos, onde muitos registros de uma entidade estão relacionados com muitos registros de outra entidade.*
- @MappedSuperclass:
>*usada em classes que contêm campos e métodos que devem ser herdados por entidades filhas.*

<br>

## 📜 N

- @NonNull:
>*gera verificações de nulos em tempo de compilação.*
- @NotBlank:
>*valida que um atributo do tipo String não pode ser nulo e nem vazio.*
- @NotNull:
>*checa se o valor anotado não é nulo (null) em tempo de execução.*
- @NoArgsConstructor:
>*gera um construtor sem parâmetros automaticamente.*
- @NotEmpty:
>*valida que a propriedade não é nula nem vazia. Pode ser utilizada com String, Collection, Map ou array.*

<br>

## 📜 O

- @Order:
>*define a ordem de execução de um componente ou método dentro de um sistema.*
- @OneToMany:
>*especifica um relacionamento de banco de dados um-para-muitos.*
- @OneToOne:
>*especifica um relacionamento de banco de dados um-para-um.*
- @Override:
>*indica que um método em uma classe está substituindo um método da classe pai (superclasse) com o mesmo nome e assinatura.*

<br>

## 📜 P

- @PathVariable:
>*indica que o valor da variável virá de uma informação presente na rota.*
- @PageableDefault:
>*permite informar parâmetros padrão de paginação e ordenação.*
- @Param:
>*indica que o parâmetro é um parâmetro de um método.*
- @PatchMapping:
>*mapeia solicitações HTTP PATCH para métodos manipuladores específicos.*
- @Pattern:
>*checa se a propriedade obedece a uma expressão regular.*
- @Past:
>*valida se o valor da data está no passado.*
- @Payload:
>*usada para indicar que o parâmetro do método em que está anexada deve ser vinculado ao corpo da mensagem recebida, permitindo o acesso direto ao conteúdo da mensagem.*
- @PostMapping:
>*mapeia solicitações HTTP POST para métodos manipuladores específicos.*
- @Positive:
>*valida se o valor numérico passado é positivo.*
- @PositiveOrZero:
>*usada para validar que um valor numérico é positivo ou zero..*
- @PutMapping:
>*mapeia solicitações HTTP PUT para métodos manipuladores específicos.*
- @PreAuthorize:
>*verifica a expressão dada antes de executar o método.*
- @Primary:
>*usada quando existem dois métodos anotados com @Bean que retornam o mesmo tipo de objeto. Indica qual deles será injetado por padrão quando for solicitado.*
- @Profile:
>*indica em qual perfil (profile) o bean deve ser carregado.*

<br>

## 📜 Q

- @Query:
>*permite criar instruções SQL personalizadas e expor essas instruções como métodos DAO.*
- @Qualifier:
>*usada para especificar qual bean deve ser injetado em um componente Spring quando há ambiguidade.*

<br>

## 📜 R

- @RabbitListener:
>*usada para marcar métodos que desejam ouvir mensagens de uma fila RabbitMQ, permitindo a configuração automática de um consumidor para processar essas mensagens quando são recebidas.*
- @RestController:
>*marca a classe como um controlador no qual cada método retorna um objeto de domínio em vez de uma visão.*
- @RestControllerAdvice:
>*torna uma classe um componente especializado em tratar exceções e o retorno dos métodos dessa classe deve ser inserido no corpo da resposta HTTP e convertido para JSON.*
- @Repository:
>*define uma classe como pertencente à camada de persistência (repository).*
- @RequestBody:
>*indica que o valor do objeto virá do corpo da requisição.*
- @RequestMapping:
>*mapeia solicitações da web para classes manipuladoras específicas e métodos manipuladores.*
- @RequestParam:
>*mapeia os parâmetros HTTP para argumentos de métodos.*
- @Required:
>*usada para marcar uma propriedade de bean como obrigatória, exigindo que ela seja definida por meio de injeção de dependência, podendo causar uma exceção de configuração se não for configurada.*
- @RequiredArgsConstructor:
>*cria um construtor com todos os atributos finais da classe automaticamente.*
- @ResponseBody:
>*transforma um objeto Java retornado pelo controller em uma representação de recurso solicitada por um cliente REST.*
- @ResponseStatus(HttpStatus.OK):
>*indica que quando a requisição é bem-sucedida, o código de status HTTP retornado deve ser "200 OK".*
- @ResponseStatus(HttpStatus.CREATED):
>*retorna um status code que indica que algum recurso foi criado na aplicação.*
- @ResponseStatus(HttpStatus.NO_CONTENT):
>*retorna um status code que indica que a solicitação HTTP foi concluída com êxito e não há corpo de mensagem.*

<br>

## 📜 S

- @Service:
>*marca uma classe Java como um serviço que executa alguma lógica de negócio.*
- @SequenceGenerator:
>*usada para especificar a sequência de banco de dados usada pelo gerador de identificadores da entidade atualmente anotada.*
- @Setter:
>*cria métodos de configuração (setters) para todos os atributos da classe automaticamente usando o Lombok.*
- @Size:
>*verifica se a quantidade de elementos está entre um tamanho mínimo e máximo especificado, aplicável a tipos como Strings, Collections, Maps e arrays.*
- @Slf4j:
>*gera automaticamente um campo de logger privado e estático na classe com base no nome da classe em que é aplicada.*
- @Spy:
>*cria um "espião" de um objeto, permitindo a verificação de interações com o objeto durante testes.*
- @SecurityRequirement(name = "bearer-key"):
>*especifica um requisito de segurança (como autenticação do tipo Bearer token) para uma operação.*
- @SpringBootTest:
>*cria o contexto da aplicação Spring para fins de teste, permitindo a injeção de dependências e outras funcionalidades do framework.*
- @SpringBootApplication:
>*indica que a classe principal é uma aplicação Spring Boot.*
- @SuppressWarnings("unchecked"):
>*usada para suprimir avisos do compilador relacionados a operações de conversão não verificadas.*
- @Scope:
>*permite especificar se um bean deve ser único em todo o contexto da aplicação (singleton), se deve ser criado uma vez por requisição (request), uma vez por sessão (session), ou se deve ser um novo bean a cada vez que for injetado (prototype).*
- @StepScope:
>*usada para indicar que um bean deve ser criado ou obtido em tempo de execução para cada execução de uma etapa (step) em um job de lote.*

<br>

## 📜 T

- @Table:
>*especifica o nome da tabela principal associada à entidade anotada atualmente.*
- @Test:
>*define um método como um teste.*
- @TestMethodOrder(MethodOrderer.OrderAnnotation.class):
>*executa os testes em ordem especificada pela anotação @Order().*
- @TestMethodOrder(MethodOrderer.MethodName.class):
>*executa os testes em ordem alfabética pelo nome do método.*
- @TestMethodOrder(MethodOrderer.Random.class):
>*executa os testes em ordem aleatória.*
- @TestMethodOrder(MethodOrderer.DisplayName.class):
>*executa os testes em ordem especificada pela anotação @DisplayName().*
- @ToString:
>*gera uma implementação do método toString.*
- @Transactional:
>*utilizada nos métodos que requerem transações, garantindo que as operações sejam executadas atomicamente.*
- @Transient:
>*indica que um campo não deve ser persistido na base de dados.*

<br>

## 📜 V

- @Valid:
>*indica que o valor do objeto virá do corpo da requisição e precisa ser validado de acordo com as regras de validação definidas.*
- @Value:
>*fornece uma maneira de injetar valores de propriedades em componentes.*

<br>

## 📜 W

- @WithMockUser:
>*permite a execução de testes usando um usuário fictício autenticado.*

<br>

## 👨‍🎓 Autor

#### Lucas Araujo

<a href="https://www.linkedin.com/in/lucarauj"><img alt="lucarauj | LinkdeIN" width="40px" src="https://user-images.githubusercontent.com/43545812/144035037-0f415fc7-9f96-4517-a370-ccc6e78a714b.png" /></a>

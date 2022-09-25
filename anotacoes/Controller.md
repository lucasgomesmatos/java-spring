### JAVA Spring Boot

### Controller

```java

    // Dizer para o Spring é um componente Spring
    // Além também dizer consegue tratar requisições HTTP
    @RestController 
    public Class ClienteController {
    
        // endpoint de mapeamento do método
        @GetMapping("/clientes") 
        public String listar() {
            return "lista de clientes";
         }
}

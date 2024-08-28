### Definiciones de Anotaciones

- **@RestController**: Se usa para definir una clase de controlador en Spring MVC. Combina `@Controller` y `@ResponseBody`, por lo que todos los métodos de la clase devuelven datos en lugar de vistas.

- **@RequestMapping("item")**: Mapea las solicitudes HTTP a los métodos del controlador. En este caso, todas las solicitudes bajo `/item` serán manejadas por este controlador.

- **@Autowired**: Se utiliza para inyectar dependencias automáticamente. En este caso, se inyecta la instancia de `ItemService` en `ItemController`.

### Método `toString` en `GroceryItem`

El método `toString()` en la clase `GroceryItem` convierte el objeto a una representación en cadena que es útil para depuración y registro. Este método sobreescribe el método `toString()` heredado de `Object` y proporciona una manera más legible de mostrar la información del objeto.

### Etiqueta `@Override`

La etiqueta `@Override` se utiliza para indicar que un método está sobrescribiendo un método de la superclase. Es una buena práctica utilizarla, ya que ayuda a evitar errores, como una firma de método incorrecta.

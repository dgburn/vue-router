# Интеграция с компонентами Vue

### Добавляемые свойства

Нижеперечисленные свойства становятся доступными в каждом дочернем компоненте при передаче роутера через опцию `router` корневого инстанса приложения.

- #### $router

  Инстанс роутера.

- #### $route

  Объект [Route](route-object.md), соответствующий текущему активному пути. Это свойство доступно только на чтение и его параметры иммутабельны, но над ними можно установить наблюдение.

### Доступные опции

- **beforeRouteEnter**
- **beforeRouteLeave**

  См. [раздел документации о сторожевых хуках](../advanced/navigation-guards.md#incomponent-guards).

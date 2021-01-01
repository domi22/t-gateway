1- 如何按照服务名动态路由


2- 如何配置路由规则


3- 如何使用过滤器


4- 如何让自定义的过滤器在某一个路由规则上生效
在filter中判断路由ID.
Route route =(Route) exchange.getAttributes().get(ServerWebExchangeUtils.GATEWAY_ROUTE_ATTR);
String id = route.getId();



5- 配置路由权重


6- 内置的限流的过滤器


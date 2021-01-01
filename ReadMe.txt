1- 如何修改配置，不重启生效？


2- 如何让自定义的过滤器在某一个路由规则上生效
在filter中判断路由ID.
Route route =(Route) exchange.getAttributes().get(ServerWebExchangeUtils.GATEWAY_ROUTE_ATTR);
String id = route.getId();



3- 配置路由权重


4- 内置的限流的过滤器

5- 集成sentinal


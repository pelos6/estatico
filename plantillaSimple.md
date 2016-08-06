[inicio](inicio.html) / [miMundo](miMundo.html) / [plantillas](plantillas.html) / plantilla simple
#  Plantilla simple
<!-- MarkdownTOC -->

- [Proposito](#proposito)
- [Bower](#bower)

<!-- /MarkdownTOC -->

# Proposito
- Los problemas que voy encontrando y (a veces) resolviendo.
#  Bower
bower install me da este error
```
bower install
"appbower" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.
```
asi que instalo bower otra vez
```
npm install -g bower
```
da ahora este error
```
bower invalid-meta  The "name" is recommended to be lowercase, can contain digits, dots, dashes
```
reviso bower.json y name es correcto !!!!
```
bower install --verbose -- force
```  
ahora funciona 



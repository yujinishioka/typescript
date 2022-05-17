# Decorators

para utilizar os decorators, primeiro precisa ativar a função '**experimentalDecorators**' em '**tsconfig.json**'

## Formato básico

```
export function nomeDaFuncao() {
    return function(
        target: any,
        propertyKey: string,
        descriptor: PropertyDescriptor
    ) {
        return descriptor;
    }
}
```
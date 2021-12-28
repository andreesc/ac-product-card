# AC-PRODUCT-CARD

Este es un paquete de pruebas de despliegue de NPM.

### Andrés Cortés | Curso de Fernando Herrera.

## Ejemplo
```
import {
    ProductCard, ProductImage, ProductTitle, ProductButtons
} from 'ac-product-card''
```


```
<ProductCard 
    product={product}
    initialValues={{
        count: 4,
        maxCount: 10,
    }}
>
    {
        ({reset, count, maxCount, isMaxCountReached, increaseBy}) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons/>
            </>
        )
    }
</ProductCard>
```
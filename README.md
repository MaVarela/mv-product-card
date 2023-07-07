# MV-Product-Card

Este es un paquete de pruebas de despliegue en npm

### Mariano Varela

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'mv-product-card';
```

```
<ProductCard
  key={product.id}
  product={product}
  initialValues={{
    count: 4,
    // maxCount: 10,
  }}
>
  {
    ({ reset, isMaxCountReached, count, increaseBy }) => (
      <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
      </>
    )
  }
</ProductCard>
```
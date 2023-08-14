#SA-Product-Card

Este es un paquete de pruebas de despliegue de NPM

### Sebastian Allende

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'sa-product-card';
```

```
 <ProductCard
        key={product.id}
        product={product}
        initialValues={{
          count: 4,
          maxCount: 10
        }}
      >
        {
          ({
            reset,
            count,
            increaseBy,
            isMaxCountReached
          }) => (
            <>
              <ProductImage />
              <ProductTitle />
              <ProductButtons />
            </>
          )
        }
      </ProductCard>
```

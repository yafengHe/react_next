## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

在 async 使用

```
import {getTranslations} from 'next-intl/server';
const t = await getTranslations('Basic');
{t('initText')}
```

非 async 使用

```
import {useTranslations} from 'next-intl';
const t = useTranslations('Basic');
 {t('initText')}
```

https://blog.csdn.net/randy521520/article/details/130066048

https://zhuanlan.zhihu.com/p/382916768

国际化：
https://zhuanlan.zhihu.com/p/690550165

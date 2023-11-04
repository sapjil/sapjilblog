---
title: Changed to Astro
pubDate: 2023-11-03
tags: ['sapjil', '삽질', 'Astro']
description: Gridsome에서 Astro로 넘어오게 된 이야기
categories:
  - www
# heroImage: '/blog-placeholder-about.jpg'
# heroImage='/blog-placeholder-about.jpg'
---

<img src="https://live.staticflickr.com/65535/53308273903_1d6030c9d0_b.jpg" alt="blog-placeholder-astro"/>

그동안 Gridsome을 사용해서 그나마 남겨놓고 있던 Sapjil이지만, 일년전인가 한번, 그리고 몇달전에 다시 한번 업데이트를 위해 작업을 하려 할때마다 오류와 맞딱뜨리며 그때마다 포기를 하게 되었는데요.

최근 Astro에 관심이 생겼습니다. 새로 설치를 해도 실행이 되질 않는데 이유는 모르겠고 되지도 않는 Gridsome을 해결하기 위해 머리를 감싸고 외국 사이트를 돌아다니는 것보다 스트레스를 받지 않을 것 같아 Astro로 옮기기로 했습니다. 이사 자체는 어렵지 않았습니다.

## 기존 Gridsome

```md
---
title: Changed to Astro
date: 2023-11-03
tags: ['sapjil', '삽질', 'Astro']
description: Gridsome에서 Astro로 넘어오게 된 이야기
categories:
  - www
---
```

## Astro

```md
---
title: Changed to Astro
pubDate: 2023-11-03
tags: ['sapjil', '삽질', 'Astro']
description: Gridsome에서 Astro로 넘어오게 된 이야기
categories:
  - www
---
```

`.md` 파일의 기본적인 부분의 수정, `date`를 `pubDate`로 바꾸기만 해도 페이지 표시에는 문제가 없었습니다. 카테고리나 페이지간 이동등 몇몇 부분은 좀 더 익혀봐야 겠지만 현재로선 마음에 드는 것 같습니다.
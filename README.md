# CursedGboard — публичная витрина релизов

Здесь **нет исходников**. Это только витрина, из которой Morphe читает обновления:

- `patches-bundle.json` — манифест (версия, описание, ссылка на `.mpp`);
- `patches-list.json` — список патчей для UI;
- Releases — готовые бандлы `patches-<version>.mpp`.

Исходники и сборка живут в приватном репозитории; витрина обновляется автоматически
из CI после каждого тега.

## Как добавить источник в Morphe

1. Открой в Morphe: **Add source** → **GitHub**;
2. введи `cursednul/gboardpatch-releases`;
3. сохрани и нажми **Refresh / Check for updates**.

Или прямой ссылкой:

```
https://morphe.software/add-source?github=cursednul/gboardpatch-releases
```

## Что ставится

Бандл `patches-<version>.mpp` — набор патчей `Cursed Patches` для
`com.google.android.inputmethod.latin` (Gboard), собранный под
`18.5.4.993608717-release-arm64-v8a`.

Релизы подписаны только как артефакты GitHub. Исходный код, история коммитов
и ключи сюда не попадают.

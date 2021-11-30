# Обзор

{% embed url="http://fs5.directupload.net/images/160306/bpdp2375.jpg" %}

MythicMobs основан вокруг настраиваемых сущностей/мобов, и есть множество опций и атрибутов, которые вы можете использовать. Ниже вы найдете полный список опций/атрибутов, которые могут быть добавлены к вашим пользовательским творениям.

Большинство из них необязательны, то есть вам не придется настраивать весь список каждый раз, когда вы создаете нового моба. Все, что действительно необходимо, это internal\_mobname и Type.

Вы можете создать любое количество файлов в папке Mobs, и они могут быть названы как угодно, лишь бы файл заканчивался на .yml.

```yaml
iternal_mobname:
  Type:
  Display:
  Health:
  Damage:
  Armor:
  BossBar:
  Faction:
  Mount:
  Options:
  Modules:
  AIGoalSelectors:
  AITargetSelectors:
  Drops:
  DropsPerLevel: (Below v4.4 only)
  DamageModifiers:
  Equipment:
  KillMessages:
  LevelModifiers:
  Disguise:
  Skills:
```

## Разбивка на варианты

### internal\_mobname:

Эта строка будет служить внутренней ссылкой на вашего моба в MythicMobs и может быть любым именем, которое вам нравится. Оно должно быть буквенно-цифровым и чувствительным к регистру. Примеры:&#x20;

* super\_zombie:&#x20;
* SuperZombie:&#x20;
* superzombie:

### Type: \[Тип мобов].

Это поле определяет, на каком типе мобов будет основано ваше создание. Полный список доступных сущностей: Типы мобов Примеры:

* Type: zombie
* Type: SKELETON

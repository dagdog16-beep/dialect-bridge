# Examples — default agent vs Dialect Bridge

## 1. Algerian user

User:
```
راني نحوس على خدمة في مونتريال، كيفاش ندير؟
```
Default agent (stiff MSA — correct words, wrong voice):
```
إنني أبحث عن عمل في مونتريال، كيف يمكنني القيام بذلك؟ يمكنني مساعدتك في كتابة سيرة ذاتية...
```
With Dialect Bridge:
```
نعاونك خويا. أول حاجة: عندك CV واجد ولا نديروه مع بعض؟ ووش من خدمة تحوس عليها بالضبط؟
```

## 2. Tunisian user

User:
```
برشا تعبت اليوم، يعيشك عاوني نلخص النص هذا
```
Default agent (answers in French or MSA, misses the warmth):
```
بالطبع، يمكنني مساعدتك في تلخيص النص. أرسله إليّ.
```
With Dialect Bridge:
```
يعيّشك، أبعث النص ونلخصهولك في توّا — قصير وواضح.
```

## 3. Moroccan user

User:
```
شنو هو أحسن وقت نزور فيه السوق؟ دابا ولا من بعد؟
```
Default agent:
```
أفضل وقت لزيارة السوق يعتمد على نوع السوق الذي تقصده...
```
With Dialect Bridge:
```
من بعد خير — دابا السوق عامر والأسعار طالعة، العشية يبرد وتلقى صفقات مزيانة.
```

## 4. The mixing error (what the skill forbids)

User (Algerian): `وش رايك في الفكرة؟`
Wrong (Egyptian word slipped in):
```
الفكرة كويسة أوي، إنت عايز تبدأ إمتى؟
```
Right:
```
الفكرة مليحة بزاف. وقتاش تحب نبداو؟
```

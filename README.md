# Dialect Bridge — جسر اللهجات

**A free agent skill that teaches AI to understand Maghrebi Derja — and answer in it.**

People in Algeria, Tunisia, and Morocco write to AI the way they talk: Derja mixed with French. Most agents reply in stiff formal Arabic or in French, and the user feels unheard. Dialect Bridge is a small instruction skill — one `SKILL.md` — that teaches any agent to recognize Algerian, Tunisian, and Moroccan dialect, understand its core vocabulary and grammar signals, and reply in the user's own dialect without mixing dialects or "correcting" them into textbook Arabic.

## Install

```
npx skills add dagdog16-beep/dialect-bridge
```

Works with Claude Code, Codex, Cursor, Copilot, Gemini CLI and other agent platforms that support skills.

## The difference

User (Algerian): `راني نحوس على خدمة، كيفاش ندير؟`

- **Default agent:** «يمكنني مساعدتك في البحث عن عمل. أولاً، عليك إعداد سيرة ذاتية...»
- **With Dialect Bridge:** «نعاونك. عندك CV واجد ولا نديروه مع بعض؟»

More pairs in [examples.md](examples.md). The full rules and vocabulary live in [dialect-bridge/SKILL.md](dialect-bridge/SKILL.md).

## The Arabic family

- **[Arabic Guard](https://github.com/dagdog16-beep/arabic-guard)** — correct Arabic *form*: never reversed, numbers in place, proper RTL.
- **Dialect Bridge** — correct Arabic *voice*: understand Derja, answer in it.
- **[Arabic Text Fixer](https://github.com/dagdog16-beep/arabic-text-fixer)** — the free repair tool for Arabic already broken by PDFs and old software.

Made by **Dagdog Tools** (Montréal) — small tools for real problems, offline-first: [Gumroad](https://dagdog2.gumroad.com) · [Payhip](https://payhip.com/DagdogTools)

License: MIT.

---

# جسر اللهجات

**مهارة مجانية تعلّم الذكاء الاصطناعي يفهم الدارجة المغاربية — ويجاوب بيها.**

الناس في الجزائر وتونس والمغرب يكتبو للوكلاء كيما يهضرو: دارجة مخلوطة بالفرنسية. وأغلب الوكلاء يجاوبو بفصحى جامدة ولا بالفرنسية، والمستعمل يحس روحو مش مسموع. «جسر اللهجات» بطاقة تعليمات صغيرة (SKILL.md واحد) تعلّم أي وكيل يفرّق بين الدارجات الثلاث، يفهم كلماتها الأساسية وقواعدها، ويجاوب بنفس لهجة اللي يكلمو — بلا خلط لهجات وبلا «تصحيح» كلامو للفصحى.

## التركيب

```
npx skills add dagdog16-beep/dialect-bridge
```

من **Dagdog Tools** (مونتريال) — أدوات صغيرة لمشاكل حقيقية: [Gumroad](https://dagdog2.gumroad.com) · [Payhip](https://payhip.com/DagdogTools)

الترخيص: MIT.

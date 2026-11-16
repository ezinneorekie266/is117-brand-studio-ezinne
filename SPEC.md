# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: Baseline ready to try; brand decisions pending.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Pending learner scope agreement.
- Next small decision: Confirm the first slice after trying the neutral storefront.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card | Primary audience | Secondary audience |
|---|---|---|
| Person in a concrete situation | College students and young adults choosing casual clothing for everyday wear. | Adults looking for simple, versatile clothing for everyday use. |
| Goal or meaning they seek | To express their individuality and personality through personal style. | To create different looks using simple clothing. |
| Concern before choosing | A plain T-shirt may look ordinary or fail to reflect their personality. | A basic T-shirt may offer limited opportunities for personal expression. |
| What the page should help them decide | Whether Thread & Story's white T-shirt is a good starting point for self-expression. | Whether the T-shirt is versatile enough for their personal style. |
| Evidence or assumption | Assumption; not validated through customer research. | Assumption; not validated through customer research. 

## Early brand brief
| Decision | Agreement |
|---|---|
| Brand name | Thread & Story |
| One-sentence promise | A simple T-shirt becomes a way to express your personality and tell your story. |
| Primary archetype: the brand's character | The Creator — expressing individuality through personal style. |
| Three voice traits | Friendly, confident, and expressive. |
| One example line in this voice | Same Shirt. Different Story. |
| Learner's predicted audience effect | Visitors will understand the brand's focus on self-expression and feel encouraged to explore the storefront. |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item | Agreement or evidence |
|---|---|
| Shared headline / support / action | “Same Shirt. Different Story.” / “Express your personality and tell your story.” / “Explore the collection.” |
| Modernist preview, reference, and annotations | Clean grid, restrained colors, simple typography, and balanced spacing. Reference: Swiss International Style. Intended effect: clarity and order. Risk: may feel too plain for a self-expression brand. |
| Postmodernist preview, reference, and annotations | Bold typography, expressive color accents, playful composition, and layered visual elements. Reference: Memphis Design. Intended effect: individuality and creativity. Risk: too many decorative elements could distract from the product. |
| Chosen direction and reason | Postmodernist-inspired design, balanced with clear navigation and readable text, because it better communicates individuality and self-expression. |
| Original SVG logo | Thread & Story wordmark using the brand name and tagline. |
| Monochrome and small-size variants | Use a single-color version and a simplified version that remains readable at small sizes. |
| Logo review at actual use size | Review the logo in the navigation area and at a smaller display size before final approval. |
| Shared palette, typography, spacing, and assets | Use the same colors, typography, spacing, wordmark, and product imagery across the storefront and style guide. |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle | Actual copy or interaction | Visitor benefit / factual support |
|---|---|---|
| Emotional appeal / self-expression | The headline says “Same Shirt. Different Story.” The supporting copy explains that a simple T-shirt can express identity, creativity, and personal style. | Helps visitors understand the brand's message and consider how clothing can reflect their individuality. |
| Transparency / informed choice | Visitors can select S, M, L, or XL and try the demo bag. The page labels the $28 price as fictional and explains that the bag resets on reload and has no checkout. | Visitors can explore the demonstration honestly, understand its limitations, and make an informed decision. |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Principle | Actual copy or interaction | Visitor benefit / factual support |
|---|---|---|
| Emotional appeal / self-expression | The headline says “Same Shirt. Different Story.” and the supporting copy explains that a simple T-shirt can express identity, creativity, and personal style. | Helps visitors understand the brand's message and consider how clothing can reflect their individuality. |
| Transparency / informed choice | Visitors can select S, M, L, or XL and try the demo bag. The page labels the $28 price as fictional and explains that the bag resets on reload and has no checkout. | Visitors can explore the demonstration honestly, understand its limitations, and make an informed decision without being misled into thinking a real purchase is taking place. |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.

## Review 2 — Plan: Thread & Story

### 1. Compare two design approaches

**Approach A — Product-first storefront**

A simple shopping layout that emphasizes the T-shirt, price, available sizes, and a straightforward checkout. Its main advantage is simplicity and quick product selection.

**Approach B — Expressive, story-led storefront (chosen)**

A storefront that combines clear product information with the Thread & Story promise, “Same Shirt. Different Story.” It retains straightforward shopping navigation while using the existing visual identity to communicate individuality and self-expression.

**Decision:** Choose Approach B because it carries forward the established brand identity while keeping product selection and checkout understandable.

### 2. User stories

1. As a visitor, I want to see the T-shirt, price, and available sizes so that I can make an informed selection.
2. As a shopper, I want to select a size and add the shirt to my bag so that I can review my choice.
3. As a shopper, I want to review my selected item, size, and price before checkout so that I can confirm my order details.
4. As a shopper, I want to complete a simulated checkout and receive a confirmation so that I can understand the demonstration purchase process.
5. As a returning visitor, I want demonstration order information saved in SQLite so that I can retrieve it after closing and reopening the application.

### 3. Essential features and observable checks

| Feature | Observable check |
|---|---|
| Product display | The T-shirt, brand name, tagline, and fictional price are visible. |
| Size selection | S, M, L, and XL can be selected. |
| Shopping bag | The selected item and size appear correctly; an item can be removed. |
| Simulated checkout | Required information is validated, and a successful demonstration produces a confirmation. |
| SQLite storage | A completed demonstration order is saved and can be retrieved after the application is restarted. |

### 4. Honest persuasion

The plan retains two existing brand principles:

- **Emotional appeal and self-expression:** “Same Shirt. Different Story.” communicates individuality and personal style without promising an unsupported result.
- **Transparency and informed choice:** The fictional $28 price and demonstration shopping bag are clearly identified. Visitors must be informed that checkout is simulated and no real payment is collected.

### 5. Technical scope

The next implementation will reuse the existing Thread & Story brand identity and storefront work where appropriate. It will add a simulated checkout and a working SQLite backend for demonstration order storage.

SQLite requires a server-side application. The static GitHub Pages storefront alone will not provide this database functionality. The implementation will therefore follow the instructor's supported SQLite starter example.

No real payment processing or actual purchase will take place.

### 6. Verification plan

- Check that all four sizes can be selected.
- Check that the correct item and size appear in the shopping bag.
- Check that required checkout information is validated.
- Check that a successful simulated checkout displays confirmation.
- Check that the order is stored in SQLite.
- Close and reopen the application and retrieve the saved order.
- Confirm that the checkout is clearly identified as a demonstration.

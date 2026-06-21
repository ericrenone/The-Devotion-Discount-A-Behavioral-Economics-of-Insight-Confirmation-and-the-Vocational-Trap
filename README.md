# The Devotion Discount: A Behavioral Economics of Insight, Confirmation, and the Vocational Trap

*Why a string of individually reasonable choices, made by people with accurate information and good intentions, reliably adds up to an unfair trade — and why that trade feels good the entire way down.*

## The question behavioral economics asks differently

The standard account of why people stay in high-effort, low-reward vocational work treats the person as either uninformed (they don't realize the cost) or as making a values trade-off (they've decided meaning is worth more than money). Behavioral economics rejects both framings. It assumes the person is paying close attention, doing something like cost-benefit reasoning in real time, and still arriving at a bad aggregate outcome — because the *architecture* of how rewards are perceived, referenced, accounted for, and remembered is systematically biased, in ways that are well documented in completely unrelated domains: gambling, labor supply, charitable giving, daycare pickup policies, taxi driving.

The claim here is narrow and falsifiable: every distortion that drives over-commitment in vocational work has an exact, previously-studied counterpart in behavioral economics, and laying the two side by side generates predictions neither literature makes on its own.

## Reward isn't a quantity, it's a value function

The neuroscience of insight and confirmation already shows that the same amount of external validation produces a shrinking subjective lift with repetition. Behavioral economics has had a precise mathematical description of exactly this shape since 1979: the prospect-theory value function, which is concave in gains (each additional unit of a good thing matters less than the last) and convex in losses (each additional unit of a bad thing matters *more* than the last), evaluated relative to a reference point rather than in absolute terms.

Apply that function to psychic income instead of money. Let `R_t` be a person's adapted reference point — their current sense of "a normal day's worth" of insight, validation, or purpose — and let `x_t` be what actually arrives. The reference point isn't fixed; it updates toward whatever was just delivered:

`R_(t+1) = R_t + θ(x_t − R_t)`, where `θ` is the adaptation rate.

And the felt payoff in any given period isn't `x_t`, it's the gap between `x_t` and the *current* `R_t`, run through a kinked, asymmetric function:

`v_t = (x_t − R_t)^α` when `x_t ≥ R_t`
`v_t = −λ(R_t − x_t)^β` when `x_t < R_t`

with diminishing sensitivity (`α, β < 1`) and loss aversion (`λ > 1`, conventionally estimated around 2).

Two things fall out of this single equation that the source material treats as separate phenomena. First, because `R_t` ratchets upward toward whatever was just delivered, sustained high performance doesn't buy lasting satisfaction — it just raises the bar for the next period, which is the formal version of "habituation" and the direct cause of effort creep: holding `v_t` constant over a career requires `x_t` to keep outrunning an `R_t` that is chasing it. Second, because losses are weighted by `λ > 1`, any dip below the *already-elevated* `R_t` — a quiet month, a rejected paper, a string of patients who don't improve — produces a hit to felt well-being roughly twice the size of the lift from an equivalent gain. People in high-psychic-income roles aren't just on a treadmill that has to keep accelerating. They're standing at the edge of a cliff that gets higher every year they perform well.

## The ledger that's never closed

One of the source accounts names its own central object a "ledger" without quite noticing what that word commits it to. Behavioral economics has a specific theory of ledgers: mental accounting, the finding that people sort resources into separate, non-fungible mental categories rather than pooling them into one bottom line, even when the categories are economically interchangeable.

Vocational workers appear to run at least two books: a *formal account* (salary, title, job security) and a *psychic account* (today's insight, today's gratitude from a patient or reader, today's sense of mattering). The reason effort-reward imbalance can coexist with a sincere, unfaked feeling of being fairly treated is that almost nobody actually performs the subtraction — formal reward plus psychic reward, minus total effort — that would reveal the imbalance as a single number. The two accounts are kept open and separately satisfying, and a surplus in one is never formally used to paper over a deficit in the other, because mental accounting specifically predicts people resist netting across categories that feel qualitatively different. A bad year in the formal account ("they passed me over for promotion again") doesn't get explicitly weighed against a good year in the psychic account ("but I finally cracked the problem") — it gets filed separately, and the books are never reconciled. This is a stronger and more mechanistic claim than "people focus on the positive." It predicts that forcing the netting — making someone write down, explicitly and side by side, what they were paid and what they gave — should itself function as a debiasing intervention, independent of any actual change in pay.

## Chasing the target, not maximizing the expectation

A classic finding in labor-supply economics looked at New York City cab drivers and found something the standard model didn't predict: drivers worked *fewer* hours on days when the wage per hour was high, and *more* hours on days when it was low — consistent with drivers carrying a daily income target in their heads and quitting once they'd hit it, rather than treating each hour as a separable decision to be made on its own marginal terms.

There is no obvious reason this kind of reference-dependent, target-seeking labor supply should be confined to money. If people carry a daily target for psychic income — a rough sense of "I need to feel like I made a difference today" or "I need to have figured something out before I stop" — the same logic predicts the opposite of what a naive effort model would say. On days when insight or confirmation arrives early and easily, a target-chaser should knock off sooner, having already hit quota. On days when nothing has clicked yet — the dry spell, the experiment that isn't working, the patient who isn't responding — the same person should work *longer*, not shorter, grinding to close the gap between what's arrived and what they need to feel okay about the day. This reframes a behavior usually read as either dedication or compulsion as a specific, previously documented labor-supply anomaly, just running on a different currency than the one it was first observed in.

## Why being underpaid can feel like proof you're real

Self-signaling models in behavioral economics start from an uncomfortable premise: people don't always know their own motives, and they use their own behavior as evidence to infer what kind of person they are — the same way they'd interpret someone else's behavior. A costly, uncompensated action is more *informative* about character than the same action taken for pay, precisely because pay supplies an alternative explanation. Working through the night for a salary tells you less about your devotion than working through the night for nothing.

This generates a genuinely uncomfortable prediction about why the most identity-fused, "called" professionals are often the ones least eager to fix their own underpayment. If staying underpaid is functioning, even unconsciously, as ongoing evidence to oneself of authentic devotion, then a raise doesn't just add money — it subtracts a piece of self-knowledge the person has been quietly relying on. Accepting fair pay makes the next act of overwork less diagnostic of character, because now there's a cheaper explanation available: maybe I'm doing this for the money. The self-signaling account predicts that resistance to compensation reform won't come only from institutions protecting their budgets. It predicts resistance *from the most devoted people themselves*, and predicts it will be strongest exactly where identity fusion with the work is strongest — which is, unhelpfully, also where the effort-reward imbalance tends to be worst.

## Wanting outlives liking, and the present always wins

The dissociation between the brain's wanting system (dopaminergic, anticipatory, drives pursuit) and its liking system (opioid-based, consummatory, registers actual pleasure) has a direct behavioral-economics partner in the gap between decision utility and experienced utility: the utility that predicts a choice and the utility actually lived through afterward are measured by different systems and can diverge for a long time before the discrepancy becomes visible even to the person living it.

Layer present bias on top of this and the failure becomes structural rather than personal. The wanting signal — the pull toward one more attempt at insight, one more chance at confirmation — is immediate, vivid, and available right now. The cost it's trading against — accumulating physiological wear, a slowly eroding baseline of actual enjoyment — is diffuse, delayed, and easy to misforecast. This is the same asymmetry behind well-documented failures to save for retirement or attend to chronic health risks, and it predicts the same thing here: an "are you still enjoying this?" check-in, asked in the moment, will reliably get a "yes" driven by intact wanting, long after liking — the thing that actually constitutes well-being — has gone net negative. People aren't lying when they say they still love the work. They're answering with the system that's still firing, not the one that's quietly keeping the real score.

## Three highs, three distortions

| High | Where the underlying mechanism shows up | The distortion it triggers |
|---|---|---|
| **Insight** | Dopaminergic burst at the moment a solution registers; unconscious associative work surfacing into awareness | Diminishing sensitivity — each additional insight delivers a smaller marginal lift than the last, at a fixed underlying difficulty |
| **Confirmation** | Reward-prediction-error signal; magnitude tracks the gap from expectation, and habituates with repetition | Reference-point ratchet + loss aversion — validation below the adapted average hurts roughly twice as much as an equivalent gain helps |
| **Purpose** | Satisfaction of autonomy, competence, and relatedness; the best-evidenced of the three highs | Self-signaling / diagnostic utility — uncompensated purpose is a *more* informative signal of authentic devotion than compensated purpose, making fair pay feel like it dilutes the proof |

## Why the recruiting pipeline doesn't reflect the lived average

A separate and well-replicated finding in behavioral economics is that people remember experiences not as a duration-weighted average of how they felt throughout, but according to the peak moment and the ending — a pattern robust enough to make people prefer, in controlled experiments, a longer painful experience with a better ending over a shorter one that simply stopped. Memory systematically discards the boring middle.

The stories that recruit the next generation into vocational fields — the mentor's best anecdote, the lab's founding myth, the one diagnosis that saved a life — are remembered utility, not experienced utility. They are, structurally, the peak and the end, stripped of the duration-weighted slog that is where the actual allostatic cost accumulated. This predicts something uncomfortable: the fields with the *worst* average effort-reward ratio over a career should produce the *most* peak/end-loaded recruiting narratives, not the least, because peak-end memory bias is precisely the mechanism that keeps a pipeline full despite a bad lived average. The people best positioned to warn newcomers accurately are, by the structure of their own memory, the worst positioned to do it.

## Why renegotiation almost never happens, even when it's offered

Two more findings explain why structural fixes — the kind the underlying physiological research says are the only real solution — get refused even when an institution actually offers them. The endowment effect shows that people demand more to give up something they already hold than they would pay to acquire the identical thing fresh, and the gap grows the longer they've held it. Escalation of commitment shows that decision-makers facing a series of sunk, identity-relevant investments tend to increase rather than decrease their commitment to a failing course of action, specifically to avoid the implication that the earlier investment was a mistake.

Put together: a tenured researcher or senior physician offered a genuinely better trade — fewer hours, more boundaries, a real renegotiation of effort against reward — isn't just weighing the new terms against the old ones. They're weighing them against an endowed identity built over years, where accepting the new terms requires implicitly conceding that the years already spent under the old terms were, to some degree, a bad trade. The resistance to a structural fix isn't stubbornness. It's the same psychology that keeps people holding a losing position past the point a fresh observer would exit, transposed from a stock portfolio onto a career.

## Why half-measures can make things worse, not better

The cleanest cautionary finding in this entire toolkit comes from a study of a daycare that introduced a small fine for picking children up late. Late pickups went *up*, not down — because the fine converted an unpriced social and moral obligation into a market transaction, and once a price existed, parents felt licensed to pay it. A closely related line of work found that small payments for an effortful task can produce *worse* performance than offering no payment at all, because a token payment signals "this is a market transaction" without paying market rates, crowding out the intrinsic motivation that was previously doing the work for free.

This predicts a specific, testable failure mode for compensation reform in vocational fields: a small, salient, explicitly monetized fix — a modest bonus, a token stipend, a "wellness allowance" — introduced without closing the actual effort-reward gap should produce a *measurable dip* in total motivation, because it makes the transaction nature of the relationship newly salient without paying for it. The relationship between "degree of monetization" and total effort should be U-shaped: high at zero (pure psychic wage, fully crowded-in) and high again once pay is genuinely fair (the trade closes cleanly), with a trough in the middle exactly where most real-world reform efforts, constrained by budgets, tend to land.

## Novel predictions

**1. Psychic income targeting.** Within-person daily time-use data should show that getting an early "win" — an insight, a piece of unprompted positive feedback, a visible result — predicts *shorter* hours that day, while a dry spell predicts *longer* hours, mirroring the reference-dependent, target-seeking labor supply already documented in hourly-wage workers. The relationship should be detectable in time-diary studies of researchers, clinicians, and creative professionals and should run opposite to a standard marginal-incentive model.

**2. Asymmetric dry-spell distress.** Drops in confirmation or recognition frequency below a person's own trailing-average reference point should produce distress responses roughly twice the magnitude of equivalent-sized upticks above that reference point — a directly measurable loss-aversion coefficient in the psychic domain, testable by comparing reactions to symmetric increases and decreases in citation counts, patient outcomes, or engagement metrics at a fixed absolute level.

**3. The monetization trough.** Institutions that introduce small, salient, explicitly monetized incentives for previously psychic-wage-only tasks, without closing the full effort-reward gap, should see total output or engagement *fall* in the near term before any larger reform could plausibly raise it — a measurable U-shape in motivation as a function of how monetized the role has become.

**4. Diagnostic resistance to raises.** Controlling for financial need, professionals with the strongest self-reported sense of calling or identity-fusion with their work should show measurably more ambivalence, hesitation, or self-reported discomfort accepting unsolicited raises or pay-equity adjustments than less identity-fused peers in the same role — because the raise dilutes a self-signal of devotion they have been unknowingly relying on.

**5. Remembered-utility recruiting skew.** Recruitment narratives and mentorship stories in vocational fields should be measurably more peak/end-loaded — concentrated on breakthrough moments and dramatic outcomes — than equivalent narrative transmission in non-vocational fields, and this skew should be *largest* in exactly the fields with the worst duration-averaged effort-reward ratios, since peak-end memory bias is the mechanism sustaining recruitment despite the bad average.

**6. Endowment-scaled renegotiation refusal.** Offered an objectively favorable renegotiation of hours or workload, willingness to accept the new terms should fall, not rise, with tenure in role — even holding the offer's objective quality constant — because the endowment effect and escalation of commitment both grow with the size and duration of the existing investment being implicitly questioned by accepting a different deal.

## Where this stops applying

The mechanisms above depend on three conditions that don't always hold. They require the two reward ledgers to stay separable — anything that forces an explicit netting of effort against total reward (transparent billable-hours accounting, gig-platform per-task pricing, public salary-and-output dashboards) should weaken the mental-accounting effect and make imbalance visible faster, which is itself a testable lever: transparency tools should reduce over-commitment not by changing pay, but by changing what gets compared to what. They require a reference point still capable of adapting upward, which is less true very early in a career, before much psychic income has been banked, and may be less true very late, after burnout has already reset expectations downward. And they require the self-signaling motive to be load-bearing in the first place — people whose sense of self-worth is anchored outside the role (family, other identities, financial independence) have less diagnostic need for uncompensated sacrifice, which is the sharpest behavioral-economics explanation available for why "decoupling self-worth from work output" functions as protection: it isn't a vague resilience skill, it's the removal of the specific incentive to keep underpayment going as evidence about the self.

## What this adds

The underlying physiological and motivational research already concludes that reframing can't fix a genuinely unbalanced trade. This account explains why reframing was never going to be the lever: the bias isn't in how people interpret a clearly visible trade-off. It's upstream of interpretation, built into how the reward itself is measured against a moving reference point, filed into a separate mental account, chased to a target rather than maximized, and used as evidence about the self rather than simply enjoyed. None of that requires anyone to be irrational in the everyday sense. Every step is the locally sensible output of decision machinery that works exactly as documented in domains that have nothing to do with vocation — and that, more than any claim about willpower or values, is what makes the trade so durable.

## Further reading

- Kahneman, D., & Tversky, A. (1979). Prospect theory: An analysis of decision under risk. *Econometrica, 47*(2), 263–291.
- Thaler, R. H. (1985). Mental accounting and consumer choice. *Marketing Science, 4*(3), 199–214.
- Thaler, R. H., & Johnson, E. J. (1990). Gambling with the house money and trying to break even. *Management Science, 36*(6), 643–660.
- Camerer, C., Babcock, L., Loewenstein, G., & Thaler, R. (1997). Labor supply of New York City cabdrivers: One day at a time. *Quarterly Journal of Economics, 112*(2), 407–441.
- Gneezy, U., & Rustichini, A. (2000). A fine is a price. *Journal of Legal Studies, 29*(1), 1–17.
- Gneezy, U., & Rustichini, A. (2000). Pay enough or don't pay at all. *Quarterly Journal of Economics, 115*(3), 791–810.
- Bénabou, R., & Tirole, J. (2003). Intrinsic and extrinsic motivation. *Review of Economic Studies, 70*(3), 489–520.
- Bénabou, R., & Tirole, J. (2006). Incentives and prosocial behavior. *American Economic Review, 96*(5), 1652–1678.
- Bodner, R., & Prelec, D. (2003). Self-signaling and diagnostic utility in everyday decision making. In I. Brocas & J. Carrillo (Eds.), *The Psychology of Economic Decisions* (Vol. 1). Oxford University Press.
- Akerlof, G. A., & Kranton, R. E. (2000). Economics and identity. *Quarterly Journal of Economics, 115*(3), 715–753.
- Loewenstein, G., O'Donoghue, T., & Rabin, M. (2003). Projection bias in predicting future utility. *Quarterly Journal of Economics, 118*(4), 1209–1248.
- Kahneman, D., Fredrickson, B. L., Schreiber, C. A., & Redelmeier, D. A. (1993). When more pain is preferred to less: Adding a better end. *Psychological Science, 4*(6), 401–405.
- Staw, B. M. (1976). Knee-deep in the big muddy: A study of escalating commitment to a chosen course of action. *Organizational Behavior and Human Performance, 16*(1), 27–44.
- Kahneman, D., Knetsch, J. L., & Thaler, R. H. (1991). The endowment effect, loss aversion, and status quo bias. *Journal of Economic Perspectives, 5*(1), 193–206.
- Samuelson, W., & Zeckhauser, R. (1988). Status quo bias in decision making. *Journal of Risk and Uncertainty, 1*(1), 7–59.

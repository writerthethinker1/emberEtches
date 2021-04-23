---
layout: post
title: 'Vaccine Effectiveness Covid-19'
category: covid-19
preview: "Are covid vaccines effective for you? Should you take them? What exactly is the advertised label '95%' or '66%' effective in laymen's terms? mathematical terms? Read on to find out! Both for you and the welfare of those around you."
published: true
---

## Vaccine Efficacy

Defining vaccine efficacy is a bit crude, but we can get an idea of efficacy if we go to a biomedical setting based on definitions available freely online.

> **Vaccine Efficacy:**[^1] Mathematically vaccine efficacy is the ability of a vaccine to ward off illness amongst those given the vaccine in comparison to those who haven't received a vial. Ideally, for an effective vaccine, we expect those who have an injection to have a significantly lower rate of infection (per population) than those who haven't. The rate of infection for vaccinated people is noted as $\alpha_v$ and the rate of infection for unvaccinated people is noted as $\alpha_{uv}$. The ratio of the two tell us "given $X$ number of people infected already having taken a vaccine, we expect $Y$ number of people to be infected without an injection." For an effective vaccine, we require in the fraction $\alpha_{v}/\alpha_{uv}$ to be significantly small as in "given 100 people infected given the vaccine we expect 100000000 people to be infected as well". And to map efficacy to a real number 0 meaning not effective and 1 meaning effective, we take the opposite of the ratio $\alpha_{v}/\alpha_{uv}$ and have

$$
\text{vaccine efficacy} = \left(1 - \frac{\alpha_{v}}{\alpha_{uv}}\right) \times 100\%
$$

What efficacy means in another sense is how well your body can have the appropriate immune response to the viral particle in question. Meaning if one is sick with particle $X$, an effective immune response is to be able to fight off an infection of $X$ without actually having the infection $X$ gives. This is typical of vaccines that are effective in producing an *anti-body* response to a single particle.

> *An effective vaccine will always help your body have the means to fight off an infection soley by what is injected inside of you.*

### Caveats post injection(s)

After one is injected with a vaccine, you may think you are immune, but really unless the vial you are given is labeled "100% effective" or maybe "90% effective" from studies done using a phase IV trial, you might not actually have immunity. These things can happen post injection and they are important for you and your health:

1. you have immunity, you body somehow by that vaccine has means to fight off an infection of what was targeted, e.g. covid-19. you have a real immune response towards what was targeted and won't be sick within chance if you were inoculated. albeit side-effects for some days that go away.
2. you don't have immunity but your body tried to generate an immune response. you didn't die or anything terrible, but were you to be inoculated with a real infection, you would face the same symptoms as those without that injection. nothing has changed.
3. you suffer severe side-effects that do not go away. perhaps leading to life-style changes or other negative things. the vaccine was both ineffective and life altering towards away normalcy. you don't have immunity.
4. you suffer the most severe side-effect of death. all with or without side-effects.

These 4 cases are what all can happen post injection and *we can't ever know which one truly happens*. However, we think it is worth being informed prior to making one's choice.

> We inform others to not mistakingly assume a vaccine will work regardless of the type you take. Carefully review or find trusty sources that have reviewed trial data for you.[^2] Make an informed decision, not a blind one. Carefully examine the 4 cases above and weigh in on the type of technology used to make the vaccine. And if you have any questions, kindly ask your local doctor or even the person injecting you about it. They might be able to tell you more. We have linked several credible sources[^3] for you to verify the type of technology being used, and plan on making overviews of the vaccines that being given on a daily basis in most countries globally.

***

### Probability and Efficacy

We also give a probabilistic account of what efficiacy is. It is basic and uses conditional logic.

When a vaccine is $\alpha\%$ effective, it means that for a *range* of values *within* a certain *degree* of that number $\alpha$ the true chance of a population having an effective response is somewhere around $\alpha$. All without knowledge of the *real efficacy rate* $a$. All vaccines, like pfizer's, come with a *real efficacy rate* $a\%$ that *we will never know* and clinical trials show us an experimental or empirical rate $\alpha\%$ that is correct *within degrees* and is *never exact* but correct *within measurement* and prone to error.

> The more time and effort we make into a study: larger sample size, data analysis, and more trials, the better our empirical rate is within error. Meaning, the error we have decreases with more people taking the doses as well as time. Since the vaccine is already made, only sample size and time can really tell us how effective things are assuming we have logical means to assess it.

All rates are *conditional on their data*. So, when we have a statement like

> "pfizer's vaccine is just out! it's 95% effective!"

It really means:

$$
\mathbb{P}(\text{effective}| \text{trial data}) \approx 95\%
$$

And the rate "95%" is an overall rate for an entire population in high number. An equivalent statement we can make is

> "pfizer's vaccine is just out! it's 5% ineffective!"

Meaning that some people will inevitably find the vaccine not working for them, but *they won't know* and for those that do find it working long term with little to no side effects, maybe herd immunity can help the rest of us.

The advertised efficacy rate assumes...

1. all people in the population are *identical*: same age, health, pre-existing conditions, gender, class, and so on...everyone is a mirror copy of each other or can be roughly identical
2. the trial data is exact and within probability, the appropriate number of volunteers were there to have an effective confidence or credible region
3. the biomedical means to ascertain immunity are not subject to error, within reason. the biomedical methods also are *sufficient* for determining immunity correct to: short term side-effects, long term side-effects, and overall immune response. all relative to what we currently know about the disease. it is *knowledge dependent* as well as *technology dependent*.
4. the study is replicable and shows *consistency* among various subjects. it is in line with the scientific method.

In reality, the number "95%" is actually an *average* among many worlds and is a realization of a random variable $X$ following a distribution. It's what we have conditional on what we have exactly. When real life data is present, we condition on the random variable and the distribution changes, *it changes the entropy* of $X$:

$$
X \to X|\text{data}
$$

The entropy of the conditioned value for $X$ is smaller if we have great scientific methods or nice technology. Think of the leap from a uniform to a normal curve with small variance. The smaller the variance for this simple case, the more effective the study. Less entropy means the true rate can be found within better bounds, assuming correct methods to gauge immunity and better sample size.

> rule of thumb: better technology and biomedical methods, lean toward a decrease in entropy toward the true efficacy rate $a\%$ and decrease bounds. with more time and subjects as well as better technology, we eventually will know the real efficacy rate. entropy decreases toward the actual value. it doesn't decrease away from the real rate unless something is inconsistent with what we are trying to measure and what we actually measured!

What's this mean for all the trial 'efficacy' rates we see? All math remarks aside, it plainly means for all of us:

1. all rates are given conditional on the technology we have, people that volunteered, and errors that could have happened in the study
2. more time and effort spent on phase IV trials can actually tell us the real rate within bounds. make us closer to it, we mean.
3. the rates assume a uniform population: age, gender, ethnicity, occupation, health, and many more factors. (this is false, we have a diverse population of people instead).

Due to this, please question for yourself if you are...

1. elderly or young
2. in good health
3. male/female
4. of different ethnicity that those in the study or if you think ethnicity plays a huge role in your immunity post vaccination

And check if you have...

1. pre-existing conditions related to your nerves, heart, lungs, kidneys, and other organs
2. occupation might interfere with your health (indoor/outdoor, strenuous activity, air pollution, etc...)

Before choosing to be vaccinated. Some elderly people have suffered the more than younger people and that might be because of how their body is.

> We aren't doctors, so we don't know exactly why this is the case, but it is worth a mention considering some of them had complications.[^4][^5][^6]

And if you really aren't certain, be sure to talk to your local physician first before and injection and clear things up. They might be able to see if you can take the vaccine that is given or available. But also make sure to follow your own thoughts.

> Plainly, doctor or not, if you don't feel comfortable taking something, you don't have to. And biomedical communities need to throughly review the data before making large scale claims for the massive population. Be curious about new technology! Curious enough to view the data from a rational point of view.

Some people might not be apt enough to have injections and having a doctor's opinion as well as your own based on how you are mentally and physically can better help you decide if any vaccine is effective or will be effective for you. We encourage informed choices.

Take care and good health throughout 2021!!! $\silver$

---

### References

[^1]: [vaccine efficacy math definition](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2536484/pdf/bullwho00089-0084.pdf)
[^2]: [mRNA vaccine safety](https://medicalxpress.com/news/2020-12-mrna-vaccine-safety.html)
[^3]: [j&j vaccine](https://www.city-journal.org/advantages-of-the-johnson-and-johnson-covid-vaccine) in addition to [adenovirus information](https://www.britannica.com/science/adenovirus) and [overview of j&j vaccine](https://news.northeastern.edu/2021/02/11/heres-how-the-johnson-johnson-vaccine-compares-to-others/)

[^4]: [covid vaccine effect on elderly people](https://www.theguardian.com/world/2020/jun/23/covid-19-vaccine-may-not-work-for-at-risk-older-people-say-scientists)

[^5]: [vaccine efficacy on older people](https://pubmed.ncbi.nlm.nih.gov/33320183/)

[^6]: [elderly deaths following vaccination](https://nltimes.nl/2021/02/08/fifteen-elderly-died-within-days-receiving-covid-19-vaccination)

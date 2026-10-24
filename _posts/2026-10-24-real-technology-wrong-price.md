---
title: Real Technology, Wrong Price
topic: finance
summary: AI is real. But the price of building it assumes returns the economics can't deliver, and the people left holding the bill won't only be investors.
---
I use AI every single day, and I even used it to help research for this article, so it’s important to preface that I'm not here to argue that it’s fake. It’s a real technology and it has the capacity to be one of the most useful inventions in the world. My argument is narrower, and I think harder to dismiss: the amount of money being spent to build it assumes returns that the economics behind it can’t deliver. That is what a bubble is, and the people who end up paying for it won’t only be the investors who chose the risk.

A bubble is not a prediction that a technology fails. Railroads were real, and so was the fiber optic cable. A bubble is what happens when price runs ahead of what the underlying cash flows justify, so that the money going in only makes sense if returns arrive that the business can’t plausibly produce.

{% include ai-bubble-definition.html %}

The shaded gap is the part that has to close, and it closes one of two ways: the cash flows catch up, or the price comes down. I’m going to use three tests to argue that that gap is too large. Does the spending pay for itself on realistic assumptions? Is the demand independent, or is part of it circular? And when it breaks, who absorbs the loss? I’ll also say where the evidence isn’t useful for my claim, because in a few places it can undermine validity. And to be clear about what I’m claiming: nothing here is a prediction of when, and nothing here is investment advice.

## The bet

Amazon, Microsoft, Alphabet, and Meta have added up to about $725 billion of capital spending in 2026, up about 77% from roughly $410 billion in 2025, according to a Financial Times tally of their guidance. Analysts model 2027 near or above $1 trillion. Almost all of it goes to chips, servers, and data centers.

{% include ai-capex.html %}

That money has to earn a return, and the scale of the return required is the problem. One analysis says the four companies’ combined capital spending will exceed their operating cash flow this year, and Bank of America projects negative free cash flow for the group through at least 2028, with the gap increasingly financed by debt. Spending more than you earn is fine if you’re early in a business that will grow into debt. It’s a bubble if the growth that’s being assumed is more than the entire market can pay for.

So what has to be true? OpenAI, the best known customer of all this capacity, reported roughly $5.7 billion in revenue in the first quarter of 2026 and $6.7 billion in the second, about triple the year before. The growth is real, and it can’t be waved away. But the same company has reportedly told investors to expect about $278 billion of negative cash flow between 2026 and 2030, and it has committed to hundreds of billions of dollars of computing capacity. Revenue is growing fast, so the question is whether it grows fast enough to cover what’s being built on its behalf.

Perhaps the best argument against me is valuation. The largest AI companies trade roughly 22 to 25 times forward earnings, well below the extremes of the dot-com years. That’s a fair point, and it’s why I define a bubble by returns on the spending, not by the price-to-earnings ratio. A multiple is a price divided by earnings, so it tells you nothing if the earnings themselves are flattered, which leads us into the next problem.

## Do the chips earn their keep?

When a company buys a chip, it doesn’t count the full cost as an expense that year. It spreads the cost over the chip’s expected life. The longer the assumed life, the smaller the yearly expense, and the larger reported profit.

{% include ai-depreciation.html %}

The large cloud companies assume their servers last roughly five to six years, up from about three years for general purpose servers from the past. Critics say that those numbers are too generous. Michael Burry, the investor best known for betting against the housing market in 2008, argues that AI chips last two to three years in practice and estimates that the longer schedules underestimate depreciation by about $176 billion. That figure is his estimate, not an established accounting fact. The pace of chips themselves supports the worry. Nvidia now releases a new generation roughly every year, which means a chip bought today competes against a much better one before the accounting says it has even half aged.

The defenders do have a real argument; an older chip doesn’t stop working when a newer one arrives. It can move from training new models to running them for customers, and because the cash cost of keeping it running is mostly electricity and hosting, it can stay profitable for years. CoreWeave, a company that rents out these chips, points to five year customer contracts and strong resale prices for older models. Amazon, notably, moved the other way and shortened the assumed life for part of its fleet from six years to five.

Even if chips last six years, they have to be replaced, and replacing them is a recurring cost of staying in business, not a one time bet. A company that has to rebuy its factory every few years needs much higher revenue to look the way its profit margins imply. My own reasoning, not a forecast: as the spending of the last two years works its way into the expense line, margins come under pressure unless revenue grows to meet it.

## Real technology, wrong price

The closest parallel is the dot-com telecom buildout. Carriers laid enormous amounts of fiber on the bet that internet traffic would grow to fill it. It did grow, but later than the plans assumed. A 2001 Merrill Lynch estimate, as reported at the time, put usage at 2.6% of roughly $90 billion of newly laid fiber.

{% include ai-fiber.html %}

The internet survived and became the platform of the next two decades. Most of the companies that built the pipes did not. That’s the pattern that's most troubling, the technology wins and the builders lose, because they paid for the future before it was ready to pay them back.

A fair reply is that fiber got used eventually, so the spending wasn’t wasted. For the economy, that’s true, but it wasn’t true for the people who paid. And fiber is a flattering comparison for one reason: fiber lasts for decades, while chips don’t. When the telecom boom ended, the next owner got cheap infrastructure that kept working. If this one ends, the data center buildings, the power connections and the cooling will outlast the chips inside them, but the chips themselves will be a generation behind. Not everything is lost, but less is left than last time.

The strongest argument for patience is productivity. Paul David’s famous paper on electrification, written about the early computer era, makes the point that power stations existed by the 1880s but the gains showed up decades later, once factories were redesigned around small motors on each machine instead of one big engine. There is early evidence of the same shape for AI. A study by McElheran, Yang, Kroff, and Brynjolfsson, using Census data from 2017 and 2021, finds that firms adopting industrial AI tend to do worse before they do better, a J-curve, with gains concentrated among the early adopters who get through the dip. The data is somewhat disputed. One economist put it as AI being “everywhere except in the incoming macroeconomic data,” while Brynjolfsson estimates US productivity grew about 2.7% in 2025, nearly double the previous decade’s pace. That’s his own estimate.

{% include ai-jcurve.html %}

I find the J-curve convincing as a description of the technology. I don’t think it rescues the price, because a J-curve is an argument about timing, and timing is exactly what bankrupts people. If the payoff takes fifteen years and the financing comes due in five, it doesn’t matter that you were right about the long run. Being right about the technology doesn’t pay interest.

## Is the demand real?

A second test is whether the demand being financed is independent of the people supplying it. Some of it plainly is. Customers are paying for these tools, but a visible slice of spending is circular. Nvidia has reportedly committed up to $100 billion to OpenAI, and OpenAI has agreed to fill facilities with Nvidia chips. OpenAI has a separate deal with AMD under which it could become one of AMD’s larger shareholders. Oracle has reportedly ordered tens of billions of dollars of Nvidia chips to serve OpenAI, and OpenAI’s total computing commitments across these deals have been reported at over a trillion dollars.

{% include ai-circular.html %}

When a supplier funds a customer, the customer’s orders overstate how much demand exists independently. That doesn’t make the deals improper. They’re disclosed, and companies argue that partnerships are necessary to build capacity fast enough. Vendor financing is also an old practice, and telecom equipment makers did it in the late 1990s, lending more money to customers so they could buy equipment. I’m not saying by any means that this is fraud. I’m saying the revenue it produces is a poor guide to what the market would pay for on its own, and nobody outside the companies can tell how large that share is. The honest answer to “how much of the demand is real?” is that it’s more than zero and less than the headlines suggest, and no one seems to know where it lies in between.

## What a pop would look like

I don't know when this ends, and I'd distrust anyone who says they do. But it's possible to describe the mechanism without a date, in the same way a rent ceiling can be described without knowing which landlord leaves first.

The spending is increasingly funded by debt and by cash flows that depend on growth continuing. The contracts for computing capacity, power and data center leases are fixed commitments that don’t shrink when revenue disappoints. If growth slows, companies cut new spending first, because it’s the only flexible part, and that hits the chipmakers and equipment suppliers whose orders were built on the assumption of more. The companies that borrowed against future revenue have to service the debt out of present revenue. This is my reasoning and I could be wrong how fast any of it happens. Each link is something a company can’t avoid doing once its numbers stop working, and that’s what makes the chain worth tracing.

## Who holds the bag

The investors who bought in know they're taking a risk. The more important question is who else is exposed without having chosen to be.

**Ratepayers.** Data centers need huge amounts of electricity, and in the largest US grid region, PJM, the price guaranteeing that electricity is available jumped from $29 to about $270 per megawatt-day between two consecutive capacity auctions. The independent market monitors attribute about 63% of the increase, roughly $9.3 billion, to data center demand.

{% include ai-pjm.html %}

Those costs reach households. Pepco’s residential customers in Washington, D.C. saw bills rise about $21 a month starting in June 2025, with the city’s consumer advocate attributing roughly half of that to capacity prices, and ICF analysts have projected residential rates in PJM could rise 30% to 60% by 2030. Estimates of the cumulative cost run from $100 billion to $163 billion through 2033 if regulators don’t intervene. In response, state legislatures, including New Jersey’s, have started moving bills to keep utility customers from footing the cost.

A Rutgers study covering 22,834 areas across 24 states from 2014 through 2024 found no robust evidence that data center openings had raised electricity bills. The authors are careful to say that period came before the hyperscaler buildout and that the real risk is regional capacity prices, not any one facility. Another analysis argues the PJM auction result reflected demand forecasts rather than actual conditions. So today’s evidence on actual household bills is thin, and what I’m describing is more of a risk and not established harm.

Despite this, it’s the risk that connects to the bubble. If power plants and transmission lines are built or contracted for demand that then doesn’t show up, the cost doesn’t disappear. Someone is still paying for the capacity, and the people with the least say in the decision are the households on the bill.

**Savers.** The ten largest companies made up about 38% of the S&P 500 in March 2026, up from about 23% in September 2019, after peaking near 41% at the end of 2025. Nvidia alone was about 7.6%.

{% include ai-concentration.html %}

Many people own those companies without ever having decided to, because they hold an index fund. The fund is supposed to be diversified, and across 500 companies it technically is, but when ten of them are over a third of it, a drop in a few AI linked names moves the entire fund. This matters for this generation more than most, as many of us will own the market through index funds for decades, so an overpriced concentration at the top isn’t someone else’s problem. If these companies are truly overpriced like I’ve been saying then their projected earnings contaminate their current prices making them absurd, so realistically if the revenue can’t catch up then there will be a recalibration of these prices.

## Price it before you cheer it

The theme of my last essay was that demands should be priced before they’re made. The same applies to optimism. A claim that AI will transform the economy can still be true and still be a bad reason to pay today’s price for it.

AI is real, and the spending assumes returns the chips, the revenue, and the electricity can’t deliver yet. Part of the demand is circular, and if it unwinds, the costs land on ratepayers and savers who never signed up for such a risky bet.

What I’m not saying is that AI is useless, that a crash is coming next quarter, or that you should buy or sell anything. I don’t know the timing, and calling a bubble early is the most common way for these essays to age badly.

What would change my mind is observable. If revenue from customers who aren’t also the suppliers grows fast enough to cover spending without more borrowing, the gap in the first figure closes from below. If the used-chip market shows older chips holding their value for five or six years, the depreciation worry fades. And if household electricity bills in the PJM states stay flat as data center loads arrive, the ratepayer risk was overstated. Despite all this, in current conditions, a bubble doesn’t look like an absurd overstatement.

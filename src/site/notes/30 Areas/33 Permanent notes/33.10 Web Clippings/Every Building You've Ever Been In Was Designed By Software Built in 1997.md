---
{"dg-publish":true,"permalink":"/30-areas/33-permanent-notes/33-10-web-clippings/every-building-you-ve-ever-been-in-was-designed-by-software-built-in-1997/","title":"Every Building You've Ever Been In Was Designed By Software Built in 1997","tags":["clippings"],"created":"2026-03-30","dg-note-properties":{"title":"Every Building You've Ever Been In Was Designed By Software Built in 1997","source":"https://www.a16z.news/p/every-building-youve-ever-been-in?utm_source=substack&publication_id=13145&post_id=192354034&utm_medium=email&utm_content=share&utm_campaign=email-share&triggerShare=true&isFreemail=true&r=eho1u&triedRedirect=true","author":["[[Joe Schmidt IV]]"],"published":"2026-03-30","created":"2026-03-30","description":"Attacking a $13 Trillion Market","tags":["clippings"]}}
---

### Attacking a $13 Trillion Market

Walk into any building and you’re surrounded by systems you never think about. The pipes routing water through every floor. The ducts pushing conditioned air into every room. The wires connecting every outlet, circuit, and fire alarm. These systems didn’t appear by magic. An architect designed the shell. A structural engineer made it stand. A team of MEP consultants (mechanical, electrical, plumbing) designed the systems inside it. A general contractor coordinated the build. Specialty trades installed everything on site.

Behind every building is a chain of firms you’ve never heard of, doing work you’ve never thought about, in a $13 trillion industry that technology has largely bypassed.

They’re all, still, running on software from 1997.

### The AEC Ecosystem

The architecture, engineering, and construction industry — AEC — is one of the largest and least digitized industries in the world. Global construction spend is [$13 trillion annually](https://www.mckinsey.com/capabilities/operations/our-insights/delivering-on-construction-productivity-is-no-longer-optional) and growing, driven by data center buildout, housing shortages, electrification, and infrastructure investment. The design and engineering services that are mission critical to construction projects account for hundreds of billions of this spend.

The industry operates by the coordination of many fragmented stakeholders. A developer or owner funds the project and sets the brief. An architect designs the building shell. MEP consultants design the mechanical, electrical, and plumbing systems that make the building function. A general contractor manages the overall build, bidding out installation work to specialty subcontractors — the electricians, plumbers, and HVAC technicians who physically put everything in place.

Inside each firm, the tools are a mess. Most of the software these firms run on was built in the late 1990s — desktop applications, installed locally, not connected or hardly connected to the cloud. They require enormous amounts of manual labor just to operate. An engineer doesn’t spend most of their day doing engineering. According to [research by Autodesk and FMI](https://www.autodesk.com/blogs/construction/construction-industry-statistics/), construction professionals spend [35% of their time, or over 14 hours a week](https://www.autodesk.com/blogs/construction/construction-industry-statistics/), on non-productive activities like looking for project information, resolving conflicts, and dealing with mistakes and rework. Much of that is just keeping disconnected tools in sync with the actual state of the project.

![](https://substackcdn.com/image/fetch/$s_!FVSe!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F7c2b3d64-d507-459a-a665-94555269bbb2_1600x1510.png)

Then there’s the problem between firms. A hospital project might involve dozens of companies — architect, structural engineer, MEP consultants, GC, a dozen specialty subs — each running their own version of their own building design file and tools, none of which are the same, almost none of which are cloud-based, all of which are sharing information through PDFs, emails, and weekly uploads to centralized drives. Changes cascade unpredictably. A structural beam moves on Tuesday. The MEP consultant doesn’t find out until Friday. By then the ductwork is routed through it. This cycle repeats constantly throughout a project. Someone has to fix it. In construction, fixing things late is orders of magnitude more expensive than getting them right early.

The consequences show up in the numbers. [85% of construction projects exceed their budgets](https://buildern.com/resources/blog/project-delays-in-construction/) and three quarters finish late. When things go wrong, they go expensively wrong: the average construction dispute in North America is worth [60.1 USD million and takes nearly 12.5 months to resolve](https://media.arcadis.com/-/media/project/arcadiscom/com/expertise/global/contract-solutions/2025/2025-15th-annual-construction-disputes-report-final-19jun25.pdf?rev=8569d68da4d44425ab37c911e699640c). In the US alone, rework, miscommunication, and time spent hunting for project data costs the industry [$177 billion every year](https://www.trimble.com/blog/construction/en-US/article/collaborative-design-sketchup-cut-construction-rework-costs) — and [more than 70% of that rework traces back to design errors](https://www.mdpi.com/2075-5309/15/4/606), not site conditions or bad weather. The drawings were wrong before anyone broke ground. Of all the software in this chain, one tool above all others defines how the industry works — and has for the better part of three decades.

![](https://substackcdn.com/image/fetch/$s_!_b3h!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F49aab16b-7ba6-4a09-9d84-e8a4927e199f_1600x718.png)

![](https://substackcdn.com/image/fetch/$s_!pS_M!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F798100df-8a18-4879-85fa-ec0a3fa38fca_1600x1491.png)

### The Monopoly Nobody Loves

In 1997, a team of engineers set out to build a better design tool for architects. Their idea was simple: model the building in 3D from the start, with every element connected to every other. Change a wall and the floor plan updates. Move a window and the ceiling elevation adjusts to scale. They called the company Revit — a contraction of “revise instantly.”

Autodesk acquired Revit in 2002 for $133 million. At the time it was considered an expensive bet. It turned out to be one of the greatest acquisitions in enterprise software history. Revit is now the standard BIM (building information modeling) authoring platform at virtually every major architecture, engineering, and construction firm in the world. It does roughly $3 billion in annual recurring revenue and has over 95% market share. It is taught in every architecture and engineering school globally and it is the system of record for the industry.

It is to AEC what Excel is to finance: the connective tissue between every firm, every workflow, and every deliverable in the industry.

The “taught in schools” detail matters more than it sounds. Almost every engineer and architect who enters the workforce already knows Revit. Every firm defaults to it because their people know it, their clients expect it, and their project libraries — custom components, material specifications, firm-specific templates built up over years — live inside it. Those libraries, or Revit “families”, are stored in Autodesk’s proprietary file formats, which don’t export cleanly to anything else. Decades of project history, component libraries, and firm-specific standards are locked inside the Revit ecosystem.

Autodesk bolted MEP functionality onto Revit in 2007 and has done very little with it since. The interface looks almost identical to what it did twenty years ago. Collaboration happens almost entirely outside of the Revit system — everyone saves their model locally, syncs it to a master file, and spends time reconciling the conflicts that accumulated. It’s the construction equivalent of finance professionals emailing Excel files back and forth.

The platform also doesn’t connect the 3D model to the physics-based calculations engineers need to run alongside it. Those happen in separate tools — notably Excel and other third-party software — all manually kept in sync by a variety of services providers. Instead of solving these problems and charging for new features, Autodesk relies on their monopoly status and drives revenue growth through price increases.

This may sound like a setup for a simple disruption story. It isn’t. Revit’s dominance has persisted not because Autodesk is protecting it aggressively, but because the problem it solves is genuinely hard. AEC design requires reasoning simultaneously about 3D geometry, physical constraints, building code, room occupancy, and equipment specs — while coordinating with teams making their own changes in parallel. Every serious challenger has stalled at the same wall: how do you teach software to actually \*understand\* a building, not just display it? How can you enable real-time collaboration? And if you can solve that, how do you get teams to trust your software when the stakes are this high?

### Why Now

For a long time, the answer was: you can’t.

Two big things have changed this calculus:

The first is obviously the advent of LLMs and vision models enabling new tools to attack problem spaces previously left unaddressed by Revit. A BIM model contains enormous amounts of metadata — room types, occupancy classifications, equipment specs, spatial relationships — but historically that data was entered inconsistently and in formats that varied by firm and project. Previous systems couldn’t make sense of it. They couldn’t look at a room and understand that it’s a server room, which means a certain cooling load, which maps to specific code requirements, which constrains where you can route the ductwork. LLMs can do that. They parse the unstructured metadata, classify it semantically, and hand structured inputs to downstream engineering algorithms.

The second is the urgency for better tooling due to enormous infrastructure buildouts. As the infrastructure for AI gets built out, many have started to note the bottleneck is in data center construction and MEP infrastructure. The talent pipeline isn’t keeping pace, and there is an existential constraint on how these firms grow and demand is met in a timely fashion.

### Three Ways to Attack a $13 Trillion Market

Given a dominant incumbent that hasn’t innovated in decades, a fragmented supply chain running on manual labor, and three technical unlocks that have only recently aligned — it’s worth being precise about how AI actually attacks this market. We’re seeing three distinct approaches in the early days of this market.

1. **Attack Revit directly.** Build a better BIM platform from scratch that’s cloud-native, AI-enabled, and collaborative by default, and win at the authoring layer. This is the most audacious approach and, historically, the graveyard. Every serious challenger for two decades has stalled trying to reach feature parity with a platform that firms have spent years customizing and their people have spent careers learning. GTM presents a few key challenges: you’re asking firms to retrain their workforce, rebuild their component libraries, and trust a new system of record with their most complex, highest-stakes work.  
	  
	[Motif](https://www.motif.io/), founded by Autodesk’s former co-CEO, is the most credible current attempt. We believe now may be the time for this to finally happen as AI makes feature parity achievable on a timeline that wasn’t possible before — and that AI demand plus the industry’s frustration with Autodesk’s stagnation has created genuine appetite for a rip-and-replace.
2. **Build new software surface area around Revit.** Don’t fight it on its own turf. Own the workflows that Revit handles poorly or not at all (of which there are many) and use that foothold to expand. Most of the actual work in AEC happens around Revit, not inside it. Revit is the system of record, but engineers spend most of their time in Excel, Word, and disconnected third-party tools. The document review process that happens before anything goes to bid — checking design documents for errors, coordination failures, and omissions across disciplines — happens entirely outside Revit. Today it’s done by humans, takes three to six weeks, costs $50,000 to $100,000 per project, and still only catches about 30% of the issues that eventually become field change orders.  
	  
	[LightTable](https://www.lighttable.ai/) is attacking exactly this workflow: AI that reads construction documents comprehensively, flags issues across disciplines, and prioritizes them by cost impact. The wedge doesn’t require anyone to change how they use Revit. It slots into the gap Revit leaves open. And every project that runs through the platform produces labeled data — here’s what the drawings showed, here’s what the issues were, here’s which ones became change orders — that makes the system more accurate over time. Nobody replaced SAP by building a better ERP. They built around it until SAP became the plumbing nobody touched.
3. **Go after the services budget directly** — the work that happens on top of Revit and has never been addressed by software at all. We believe MEP design may be the clearest opportunity here. Most of what MEP consultancies do isn’t done in Revit; it’s done by teams of engineers, often offshore, manually translating building specifications into drawings and documentation that has to be checked and revised at every step. This work has never been software-addressable before, but with AI we believe there is an opportunity to go after some of these workflows.  
	  
	This would unlock demand that was previously impossible to serve. Firms of many different kinds are sitting on backlogs of work they can’t take on because they don’t have the people. AI doesn’t just help them do existing projects faster; it lets them say yes to projects they would have turned away. [Endra](https://www.endra.ai/) is building in this space. They have built an AI-native MEP design platform that ingests building models and automates fire, electrical, and mechanical system design — work that previously took months of manual effort, done in minutes.

### Deep diving on MEP – where we’re seeing the conditions align first

MEP design is a $150 billion global services market that’s a large part of the broader AEC space. While Revit serves this area, most of the work is actually completed by services firms on top of or outside of Revit. The largest of these firms have tens of thousands of employees across dozens of countries. While these firms are critical and there is skill involved, on a time basis, almost all of their work is rote: rule-based, code-constrained. Think of the design of where to place fire alarms, power circuits, or HVAC units throughout a large buildout. Not exactly the kind of work dreams are made of.

Most of the revenue in this space flows from billable hours — manually producing designs like drawings, calculations, and documentation that a licensed engineer has to touch at every step. It’s so time-intensive that many of these firms have huge backlogs of latent demand they can’t address because they don’t have the people to do it. AI is the unlock to grow these services businesses, but even more importantly increase the rate at which society can build.

In some respects it’s quite similar to other large white collar spaces that have seen rapid AI adoption like legal, accounting, or financial research. A massive, rules-based market with legacy tools that weren’t built for the job, workflows bounded and deterministic enough to automate reliably, and a supply constraint creating genuine urgency.

### The Business Model Shift That Makes This a $100B+ opportunity

You may be thinking ok, this sounds interesting, but how big can this really be? Autodesk’s Revit product is as close to a monopoly as you can get, and it’s doing a few billion per year in revenue.

The reason this is more than a niche software opportunity comes down to what AI is actually unlocking. Across all three layers, the bottleneck is the number of qualified people available to do the available work, and the speed at which they can operate. In other words, these are capacity-constrained fields in the world of atoms, which can actually be made much more efficient with the right software.

What makes the transition easier than it sounds is that large firms have already modularized this work. Unable to hire fast enough, most of the biggest firms have offshored the repetitive, lower-complexity tasks to large teams overseas. That work is already measured in output rather than hours, already priced as a discrete deliverable, and already sits outside the core workflow. AI doesn’t need to change how firms think about this work. It just changes who, or what, is doing it.

When AI expands capacity rather than just improving tools, the pricing model changes fundamentally. The opportunity in construction isn’t charging engineers for a better Revit. It’s aligning on a share of incremental fees, for efficiency gained, for speed to build, for the change orders prevented, or for the risk eliminated from a developer’s portfolio. These opportunities are orders of magnitude larger than the significant but not enormous budget line Revit already occupies.

This pricing shift is already happening. The first AI companies in this space are creating win-win arrangements with customers on results driven per project, not simply on a per seat basis. They’re measuring success in dollars of change orders prevented and percentage points of margin recovered.

### We have to solve this problem

Right now, somewhere, an engineer is waiting for their Revit model to load. Or manually completing tasks that would cause a casual AI native observer to vomit. The consequences of these legacy tools are creating billions of dollars of waste and slowing GDP growth.

This is happening on every major construction project in the world, every week, in every city. The data centers going up to run AI. The hospitals being built to serve aging populations. The housing that cities desperately need.

The entire built world is still running on software built in 1997. That’s about to change. We’re investing accordingly.  
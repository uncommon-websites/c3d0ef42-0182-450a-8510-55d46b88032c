<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Automate investment deal sourcing through AI screening and multi-channel outbound at scale"
	subtitle="Built by former investment firm operators with 12+ years of sourcing experience. Deploy automated pipelines that deliver consistent deal flow without manual sourcing fatigue."
	imageSrc="/generated/image-a-group-of-professional-business-partner.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by leading investment firms"
	logoUrls={[
		'https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/blackstone.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/a16z.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/kkr.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Built by operators for operators"
	text="DealDeploy automates the entire deal sourcing workflow for investment firms—from AI-powered screening and data enrichment to personalized multi-channel outreach. Our proprietary systems, built on 12+ years of sourcing experience, eliminate manual research and outreach while delivering consistent, qualified deal flow. Investment firm partners finally get the sourcing capacity they need without hiring a full team."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Chen",
			position: "Partner",
			company: "Catalyst Growth Partners",
			quote:
				"DealDeploy reduced our sourcing time by 70%, freeing our team to focus on high-value relationships. We went from manually screening 200 companies per week to 1,500 qualified opportunities automatically.",
			image: "/generated/image-professional-headshot-of-an-asian-male-i.webp"
		},
		{
			name: "Elena Rodriguez",
			position: "Associate",
			company: "Summit Equity",
			quote:
				"The AI screening eliminated 40 hours of manual data entry per month. We closed our first automated deal within 90 days, and the personalized outreach maintained our firm's reputation for quality.",
			image: "/generated/image-professional-headshot-of-a-hispanic-fema.webp"
		},
		{
			name: "David Okonkwo",
			position: "Managing Director",
			company: "Frontier Capital",
			quote:
				"We cut deal sourcing costs by 60% while tripling our pipeline volume. The multi-channel approach delivered a 23% response rate, compared to our previous 8% with manual outreach.",
			image: "/generated/image-professional-headshot-of-a-black-male-ma.webp"
		}
	]}
/>

<Features
	title="Built for investment firms who need consistent deal flow"
	subtitle="End-to-end automated sourcing systems that combine AI precision with 12+ years of operator experience"
	features={[
		{
			title: "AI screening at scale",
			description:
				"Process thousands of potential deals through proprietary AI algorithms that qualify opportunities with the precision of a senior analyst. Our screening engine learns your investment criteria and continuously improves accuracy."
		},
		{
			title: "Multi-channel outbound automation",
			description:
				"Deploy personalized outreach across email, phone, and LinkedIn simultaneously without losing the human touch. Each message is AI-crafted to reflect your firm's voice while maintaining the throughput of automation."
		},
		{
			title: "Built by former investment firm operators",
			description:
				"Created by operators who lived the pain of manual sourcing at Level Equity, Resolve, Frontier Growth, and Catalyst. We understand your workflow because we built it ourselves for years."
		},
		{
			title: "Automated data enrichment",
			description:
				"Eliminate manual data entry with automated contact discovery and profile enrichment. Our systems find decision-makers, verify contact information, and populate your CRM without human intervention."
		},
		{
			title: "Custom pipeline deployment",
			description:
				"We build your sourcing engine from the ground up, tailored to your sector focus and investment criteria. You get a turnkey system, not another tool to figure out."
		},
		{
			title: "12+ years of sourcing expertise",
			description:
				"Our AI is backed by over a decade of hands-on sourcing experience across multiple investment firms. The algorithms reflect battle-tested strategies that have closed real deals."
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Stop losing deals to manual sourcing fatigue"
	subtitle="Deploy your automated pipeline in 30 days"
	description="Investment firms using DealDeploy see 70% time savings and 3x pipeline growth within 90 days. Built by former Level Equity and Frontier Growth operators who solved this exact problem. Schedule a consultation to see how we'll build your custom AI sourcing engine."
	imageSrc="/generated/image-a-business-professional-in-formal-attire.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Schedule consultation",
			variant: "primary"
		},
		{
			href: "/about",
			label: "See how it works",
			variant: "secondary"
		}
	]}
/>

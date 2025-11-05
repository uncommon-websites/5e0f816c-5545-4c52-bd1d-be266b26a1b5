<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
</script>

<CustomerCardHero
	centered={true}
	title="Never miss another service appointment"
	subtitle="Revion's autonomous AI agents answer every call, text, and message 24/7, converting missed opportunities into booked appointments for luxury dealerships."
	customers={[
		{
			name: "Michael Torres",
			position: "Service Manager",
			imageSrc: "/generated/image-medium-format-editorial-documentary-port.webp"
		},
		{
			name: "Rebecca Chen",
			position: "General Manager",
			imageSrc: "/generated/image-editorial-documentary-portrait-of-a-conf.webp"
		},
		{
			name: "David Harrison",
			position: "Service Director",
			imageSrc: "/generated/image-medium-format-editorial-portrait-of-an-e.webp"
		},
		{
			name: "Jennifer Morrison",
			position: "Operations Manager",
			imageSrc: "/generated/image-editorial-environmental-portrait-of-a-pr.webp"
		},
		{
			name: "Robert Williams",
			position: "Senior Service Advisor",
			imageSrc: "/generated/image-medium-format-editorial-portrait-of-a-se.webp"
		}
	]}
/>
<LogoScroller
	label="Trusted by luxury automotive brands"
	logoUrls={[
		'https://cdn.brandfetch.io/jaguar.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/landrover.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/porsche.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/bentleymotors.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Built for dealerships"
	text="Revion eliminates the 30-50% of service appointments lost to missed calls and slow follow-ups. Our autonomous AI agents integrate directly with your DMS to handle every customer interaction across calls, texts, and web chat, ensuring no revenue opportunity slips through the cracks. Service managers at luxury dealerships trust us to capture what matters most: every single appointment."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Henley",
			position: "Service Manager",
			company: "Jaguar Land Rover Dealership",
			quote:
				"We saw a 23% increase in service bookings within the first month. Now our team can focus on actual service work instead of constantly answering phones, and customers can book appointments 24/7 through calls and our website.",
			image: "/generated/image-editorial-documentary-style-environmenta.webp"
		},
		{
			name: "Catherine Ashford",
			position: "Operations Director",
			company: "Porsche Centre",
			quote:
				"The drastic reduction in no-shows through automatic reminders has been remarkable. Revion handles instant rescheduling and sends automated thank you messages after every visit. We're seeing our best customer retention rates ever.",
			image: "/generated/image-editorial-documentary-style-environmenta.webp"
		},
		{
			name: "Graham Stewart",
			position: "Group Owner",
			company: "Multi-Brand Luxury Group",
			quote:
				"Managing thousands of daily interactions across five locations used to overwhelm our teams. Revion's platform has become essential to our operations. Staff spend less time on repetitive calls and more time creating exceptional customer experiences.",
			image: "/generated/image-editorial-documentary-style-environmenta.webp"
		}
	]}
/>

<Features
	title="Built for dealership operations"
	subtitle="Autonomous AI agents that integrate directly with your DMS to handle every customer interaction, converting missed opportunities into revenue."
	features={[
		{
			title: "Never miss another opportunity",
			description:
				"Our AI agents answer 100% of inbound calls, texts, and messages with zero wait time, eliminating the 30-50% of revenue lost to missed customer interactions."
		},
		{
			title: "Always available, fully autonomous",
			description:
				"AI service advisors work 24/7 across all channels, handling appointment scheduling, service inquiries, and recall campaigns while your team focuses on in-person customer experiences."
		},
		{
			title: "Live DMS integration",
			description:
				"Direct connectivity with your dealer management system enables real-time inventory checks, service history access, and automated appointment booking without manual data entry."
		},
		{
			title: "Omnichannel customer engagement",
			description:
				"Deliver consistent, intelligent responses across phone calls, SMS, web chat, and third-party platforms, meeting customers wherever they prefer to connect."
		},
		{
			title: "Measurable ROI from day one",
			description:
				"Dealerships report 23% increases in service bookings and 1,315% monthly ROI through improved appointment conversion and reduced manual overhead costs."
		},
		{
			title: "Enterprise-grade security",
			description:
				"SOC2, ISO 27001, GDPR, and CCPA compliant infrastructure with end-to-end encryption protects your customer data and meets automotive industry standards."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop losing revenue to missed calls"
	subtitle="See Revion in action"
	description="Every missed call is a lost service appointment. Watch a live demo of our AI agents handling real customer interactions, or speak with our team to see how luxury dealerships achieve 23% booking increases and 1,315% monthly ROI."
	imageSrc="/generated/image-a-confident-service-manager-in-their-lat.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Watch a demo",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Talk to sales",
			variant: "secondary"
		}
	]}
/>

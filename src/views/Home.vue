<template>
	<div class="home">
		<!-- header Begin -->
		<HeaderShayna />
		<!-- Header End -->

		<!-- Hero Section Begin -->
		<HeroShayna />
		<!-- Hero Section End -->

		<!-- Hero Section Begin -->
		<WomanBannerShayna />
		<!-- Hero Section End -->

		<!-- InstaShayna Begin -->
		<InstaShayna />
		<!-- InstaShayna End -->

		<!-- PartnerLogo Begin -->
		<PartnerShayna />
		<!-- PartnerLogo End -->

		<!-- FooterShayna Begin -->
		<FooterShayna />
		<!-- FooterShayna End -->
	</div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import WomanBannerShayna from "../components/WomanBannerShayna.vue";
import InstaShayna from "../components/InstaShayna.vue";
import PartnerShayna from "../components/PartnerShayna.vue";
import FooterShayna from "../components/FooterShayna.vue";

export default {
	name: "Home",
	components: {
		HeaderShayna,
		HeroShayna,
		WomanBannerShayna,
		InstaShayna,
		PartnerShayna,
		FooterShayna,
	},
};
</script>

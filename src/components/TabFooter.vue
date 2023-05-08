<template>
	<ion-page>
		<ion-tabs>
			<ion-router-outlet></ion-router-outlet>
			<ion-tab-bar slot="bottom">
				<ion-tab-button tab="home" href="#">
					<ion-icon :icon="playCircle" />
					<ion-label>Tab 1</ion-label>
				</ion-tab-button>

				<ion-tab-button tab="radio" href="#">
					<ion-icon :icon="radio" />
					<ion-label>Tab 2</ion-label>
				</ion-tab-button>

				<ion-tab-button tab="library" href="#">
					<ion-icon :icon="library" />
					<ion-label>Tab 3</ion-label>
				</ion-tab-button>
			</ion-tab-bar>
		</ion-tabs>
	</ion-page>
</template>

<script lang="ts">
import {
	IonPage,
	IonTabs,
	IonRouterOutlet,
	IonTabBar,
	IonTabButton,
	IonLabel,
	IonIcon,
} from '@ionic/vue';

import { playCircle, radio, library, search } from 'ionicons/icons';

export default {
	components: {
		IonPage,
		IonTabs,
		IonRouterOutlet,
		IonTabBar,
		IonTabButton,
		IonLabel,
		IonIcon,
	},
	data() {
		return {
			playCircle,
			radio,
			library,
		};
	},
};
</script>

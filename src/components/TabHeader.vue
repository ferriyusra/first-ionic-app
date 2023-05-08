<template>
	<ion-header>
		<ion-toolbar>
			<ion-title>Tab 1</ion-title>
		</ion-toolbar>
	</ion-header>
	<ion-buttons slot="start" style="margin-right: 8px; margin-top: 8px">
		<ion-button
			class="warning-button"
			expand="block"
			size="default"
			@click="showPrompt()"
			>Tombol Peringatan</ion-button
		>
	</ion-buttons>
</template>

<style>
.warning-button {
	color: white;
	background-color: rgb(242, 81, 81);
}
</style>

<script lang="ts">
import {
	IonHeader,
	IonToolbar,
	IonTitle,
	IonButton,
	IonButtons,
} from '@ionic/vue';

export default {
	components: {
		IonHeader,
		IonToolbar,
		IonTitle,
		IonButton,
		IonButtons,
	},

	methods: {
		showPrompt() {
			const name = 'MARIANA NAPITUPULU';
			const nim = '043352905';
			window.alert(`Error: Peringatan! ${name} ${nim}`);
		},
	},
};
</script>

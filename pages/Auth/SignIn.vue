<template>
    <div>
    <SignIn></SignIn>
    </div>
</template>

<script>
import SignIn from '../../components/amplify/SignIn.vue'
export default {
	layout: 'nouser',
	// middleware: 'guest',
	components: {
		SignIn
	}
}
</script>

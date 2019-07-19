<template>
	<main class="h-screen flex flex-col justify-center items-center">
		<slot />
	</main>
</template>

<static-query>
query {
  metaData {
    siteName
  }
}
</static-query>

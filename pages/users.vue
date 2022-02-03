<template>
    <section>
        <h1>Users Page</h1>

        <ul>
            <li v-for="user of 6" :key="user">User {{user}}</li>
        </ul>
    </section>
</template>
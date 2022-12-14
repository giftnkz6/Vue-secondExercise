<template>
    <div class="navbar">
        <nav>
            <ul>
                <li>
                    <router-link to="/">Home</router-link> |

                </li>
                <li>
                    <router-link to="/about">About</router-link>

                </li>
                <li>
                    <router-link to="/products">Products</router-link>
                </li>
                <li>
                    <router-link to="/admin">Admin</router-link>
                </li>
                <li>
                    <router-link to="/contact">Contact</router-link>
                </li>
            </ul>
        </nav>
    </div>
</template>

<script>
    export default{
        name: "NavBar"
    }
</script>

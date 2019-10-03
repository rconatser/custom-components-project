<template>
    
</template>

<script>
import { eBus } from "../main.js";

export default {
    data: () => ({
        serverID: null,
        serverStatus: "Unknown"
    }),
    created() {
        eBus.$on("DisplayServerStatus", ({ status }) => {
            this.serverStatus = status;
        });
    }
};
</script>
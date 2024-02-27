<template>
    <div>
        <ComponentFour />
        <HistoryComponent />
    </div>
</template>

<script>
import ComponentFour from "./ComponentFour.vue";
import HistoryComponent from "./HistoryComponent.vue";

export default {
    name: "ComponentThree",
    components: {
        ComponentFour,
        HistoryComponent
    }
};
</script>

<style></style>

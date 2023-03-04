<template>
    <div>
        <label for="first_name" class="block mb-2 text-sm font-medium">Starting Month</label>
        <VueDatePicker hide-input-icon v-model="date" month-picker placeholder="yyyy-mm" class="bg-gray-50"></VueDatePicker>
    </div>
</template>
  
<script>
import VueDatePicker from '@vuepic/vue-datepicker';
import '@vuepic/vue-datepicker/dist/main.css'
export default {
    components: { VueDatePicker },
    data() {
        return {
            date: null,
        };
    }
}
</script>
  
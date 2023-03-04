<template>
    <label for="countries" class="block mb-2 text-sm font-medium">Bank</label>
    <select required placeholder="No filter applied" id="countries"
        class="select bg-gray-50 border border-gray-300 text-sm rounded-smblock w-full p-2.5">
        <option value="" selected>
            <div class="text-gray-400">No filter applied</div>
        </option>
        <option value="US">United States</option>
        <option value="CA">Canada</option>
        <option value="FR">France</option>
        <option value="DE">Germany</option>
    </select>
</template>

<style>
select:required:invalid {
    color: #9ca3af;
}
</style>
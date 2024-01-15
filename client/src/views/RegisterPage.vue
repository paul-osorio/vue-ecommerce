<template>
  <main class="flex justify-center items-center h-screen w-screen bg-zinc-100">
    <div class="p-5 shadow-sm rounded-md bg-white">
      <div class="w-[320px]">
        <RegisterForm />
      </div>
    </div>
  </main>
</template>

<script>
import RegisterForm from "../components/Forms/RegisterForm.vue";

export default {
  name: "RegisterPage",
  components: {
    RegisterForm,
  },
};
</script>

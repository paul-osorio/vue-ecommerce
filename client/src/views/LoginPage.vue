<template>
  <main class="flex justify-center items-center h-screen w-screen bg-zinc-100">
    <div class="p-5 shadow-sm rounded-md bg-white">
      <div class="w-[320px]">
        <LoginForm />
        <div class="mt-2">
          Don't have an account?
          <router-link to="/register" class="text-blue-500 hover:underline"
            >Register here</router-link
          >
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import LoginForm from "../components/Forms/LoginForm.vue";

export default {
  name: "LandingPage",
  components: {
    LoginForm,
  },
};
</script>

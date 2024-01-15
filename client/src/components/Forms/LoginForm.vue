<template>
  <Vueform>
    <StaticElement name="h2" tag="h2" content="Login" />
    <StaticElement name="divider_1" tag="hr" />
    <TextElement name="username" placeholder="Username" />
    <TextElement name="password" input-type="password" placeholder="Password" />
    <StaticElement name="divider" tag="hr" />
    <ButtonElement
      name="submit"
      button-label="Submit"
      :submits="true"
      :full="true"
    />
  </Vueform>
</template>

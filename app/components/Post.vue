<template>
  <StackLayout class="post">
    <FlexboxLayout class="post__profile">
      <StackLayout class="post__imgProfile">
        <Image
          src="~/assets/images/rafael.jpg"
          style="width: 100%"
        />
      </StackLayout>
      <Label text="Rafael Augusto" />
    </FlexboxLayout>

    <FlexboxLayout class="post__desc">
      <Label
        textWrap
        text="Situada nos continentes fictícios de Westeros e Essos, a série centra-se no Trono de Ferro dos Sete Reinos e segue um enredo de alianças e conflitos entre as famílias nobres dinásticas, seja competindo para reivindicar o trono ou lutando por sua independência."
      />
    </FlexboxLayout>
    <Image
      class="post__image"
      src="https://s2.glbimg.com/W1MVfsy3F_8PdMZyzHgsuFRyR5A=/e.glbimg.com/og/ed/f/original/2019/01/10/mv5bnzrjzwq1ndgtnje5zi00ngfjltlkm2itmgqyy2mzmjqzngi1xkeyxkfqcgdeqxvynjc5mjg0nju._v1_sy1000_cr0015021000_al_.jpg"
    />

    <FlexboxLayout class="post__actions" justifyContent="space-between">
      <Label text="Like" />
      <Label text="Comment" />
      <Label text="Share" />
    </FlexboxLayout>

  </StackLayout>
</template>


<style lang="scss" scoped>
  .post{
    background: #fff;
    margin-top: 20;
    &__profile{
      padding: 10 10 0 10;
      Label{
        margin-left: 10;
        font-size: 13;
        font-weight: 500;
      }
    }
    &__imgProfile{
      width: 35;
      height: 35;
      border-radius: 100;
      overflow: hidden;
    }
    &__desc{
      padding: 10;
      Label{
        font-size: 12;
      }
    }
    &__actions{
      padding: 10;
      Label{
        color: #333;
      }
    }
  }
</style>

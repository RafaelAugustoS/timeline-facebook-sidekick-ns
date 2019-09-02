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

        <Image
            class="post__image"
            src="https://s2.glbimg.com/W1MVfsy3F_8PdMZyzHgsuFRyR5A=/e.glbimg.com/og/ed/f/original/2019/01/10/mv5bnzrjzwq1ndgtnje5zi00ngfjltlkm2itmgqyy2mzmjqzngi1xkeyxkfqcgdeqxvynjc5mjg0nju._v1_sy1000_cr0015021000_al_.jpg"
        />
        <!-- <FlexboxLayout class="post__desc">
            <Label
                textWrap
                :text="Description"
            />
        </FlexboxLayout> -->
  </StackLayout>
</template>


<style lang="scss" scoped>
  .post{
    background: #fff;
    margin-top: 20;
    &__profile{
      padding: 0 10 10 10;
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
  }
</style>

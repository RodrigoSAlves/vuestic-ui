<template>
  <VbDemo>
    <VbCard title="default">
      <va-avatar></va-avatar> Empty
      <br />
      <va-avatar>AA</va-avatar> Text inserted
      <br />
      <va-avatar>
        <div>AA</div>
      </va-avatar> Div inserted
    </VbCard>
    <VbCard title="Different sizes setted for avatars">
      <va-avatar size="small">S</va-avatar> small
      <br />
      <va-avatar size="medium">M</va-avatar> medium
      <br />
      <va-avatar size="large">L</va-avatar> large
      <br />
      <va-avatar size="55px">55</va-avatar> 55px
      <br />
      <va-avatar :size="66">66</va-avatar> 66
      <br />
    </VbCard>
    <VbCard title="image">
      <va-avatar src="https://randomuser.me/api/portraits/women/5.jpg"></va-avatar> square image
      <br />
      <va-avatar portrait src="https://i.imgur.com/UjiMAZj.png"></va-avatar> horizontal image
      <br />
      <va-avatar src="https://cdn.pixabay.com/photo/2016/08/03/06/22/space-1565986_1280.jpg"></va-avatar> vertical image
      <br />
    </VbCard>
    <VbCard title="default slot">
      <va-avatar>
        <img src="https://randomuser.me/api/portraits/women/5.jpg" alt="woman" />
      </va-avatar>
      image
      <br />
      <va-avatar>
        <va-icon name="iconicstroke iconicstroke-info"></va-icon>
      </va-avatar>
      icon
      <br />
    </VbCard>
    <VbCard title="square">
      <va-avatar square>AA</va-avatar>
      <va-avatar square src="https://randomuser.me/api/portraits/women/5.jpg"></va-avatar>
    </VbCard>
    <VbCard title="Avatar with icon">
      <va-avatar size="small" icon="iconicstroke iconicstroke-info"></va-avatar> small
      <br />
      <va-avatar icon="iconicstroke iconicstroke-info"></va-avatar> medium
      <br />
      <va-avatar size="large" icon="iconicstroke iconicstroke-info"></va-avatar> large
      <br />
    </VbCard>
    <VbCard title="сolor">
      <va-avatar color="danger"></va-avatar> background
      <va-avatar textColor="danger">A</va-avatar> text
    </VbCard>
    <VbCard title="font size">
      <va-avatar fontSize="15px">A</va-avatar>
    </VbCard>
  </VbDemo>
</template>

<script>
import VaAvatar from './VaAvatar'
import VaIcon from '../va-icon/VaIcon'

export default {
  components: {
    VaAvatar,
    VaIcon,
  },
}
</script>

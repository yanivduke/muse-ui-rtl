<template>
<mobile-tear-sheet>
  <mu-list>
    <mu-list-item title="Inbox">
      <mu-icon slot="right" value="inbox"/>
    </mu-list-item>
    <mu-list-item title="Starred">
      <mu-icon slot="right" value="grade"/>
    </mu-list-item>
    <mu-list-item title="Sent mail">
      <mu-icon slot="right" value="send"/>
    </mu-list-item>
    <mu-list-item title="Drafts">
      <mu-icon slot="right" value="drafts"/>
    </mu-list-item>
  </mu-list>
  <mu-divider />
  <mu-list>
    <mu-list-item title="All mail">
      <mu-icon slot="left" value="info"/>
    </mu-list-item>
    <mu-list-item title="Trash">
      <mu-icon slot="left" value="info"/>
    </mu-list-item>
    <mu-list-item title="Spam">
      <mu-icon slot="left" value="info"/>
    </mu-list-item>
    <mu-list-item title="Follow up">
      <mu-icon slot="left" value="info"/>
    </mu-list-item>
  </mu-list>
</mobile-tear-sheet>
</template>
<script>
import mobileTearSheet from '../../../components/mobileTearSheet'
export default {
  components: {
    'mobile-tear-sheet': mobileTearSheet
  }
}
</script>

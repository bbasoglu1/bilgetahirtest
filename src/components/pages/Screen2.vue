<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="b93a52e2-f010-419f-a4e1-307bd590dfc6"
    v-bind:style="{'width':'100%','height':'auto'}">
    <WAlert v-bind:fade="false" v-bind:pill="false" show="false" size="md" v-bind:isLink="false" v-bind:rotate="0"
      v-bind:squared="false" hrefLink="" alertLabel="This alert will dismiss after time lapse" background="#17a2b8"
      buttonLabel="Show alert with count-down timer" v-bind:dismissible="false" alertVariant="warning"
      dismissLabel="Close" verticalWidth="60px" buttonsVariant="info"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'buttonLabel','displayName':'ButtonLabel'},{'type':'string','propName':'alertLabel','displayName':'AlertLabel'}]}"
      verticalHeight="60px" horizontalWidth="" progressVariant="warning" v-bind:dismissCountDown="5" horizontalHeight=""
      ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#17a2b8"
      ncFocusBorderColor="#17a2b8" ncHoverBorderColor="#17a2b8" ncClickBackgroundColor="#17a2b8"
      ncFocusBackgroundColor="#17a2b8" ncHoverBackgroundColor="#17a2b8" position="relative"
      id="2892ee6c-34ca-499a-ab6c-f1fe9e05fa91"
      v-bind:style="{'color':'#FFFFFF','width':'100%','filter':'none','height':'100%','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','textAlign':'left','fontFamily':'Roboto','fontWeight':400,'lineHeight':'24px','marginLeft':'0px','paddingTop':'0px','textIndent':'0px','textShadow':'','visibility':'visible','whiteSpace':'pre-wrap','borderColor':'#fff3cd','borderStyle':'none','marginRight':'0px','paddingLeft':'0px','wordSpacing':'0px','marginBottom':'0px','mixBlendMode':'normal','paddingRight':'0px','letterSpacing':'0px','paddingBottom':'0px','textTransform':'none','backdropFilter':'none','borderTopWidth':'0px','textDecoration':'none','borderLeftWidth':'0px','borderRightWidth':'0px','horizontalHeight':'','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':2}"/>
  </DropZone>
</template>
<script>
import { mapGetters } from 'vuex';
export default {
  name: 'Screen2',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: { ...mapGetters('source', ['getApiMappingWithChain'])},
  methods: {bindSource(chain) { return this.getApiMappingWithChain(chain); }},
  watch: {},
};
</script>

<style lang="scss" scoped>@media (min-width: 1024.05px){
[id='b93a52e2-f010-419f-a4e1-307bd590dfc6'] {
             display: grid; 
             grid-template-columns: 49.404296875rem 20.703125rem 29.892578125rem;
             grid-template-rows: minmax(12.94921875rem, max-content) minmax(2.96875rem, max-content) minmax(67.01171875rem, max-content);
          }
[id='2892ee6c-34ca-499a-ab6c-f1fe9e05fa91']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(16rem, 12px),1.25rem);
          }
}
@media (min-width: 768.05px) and (max-width: 1024px){
[id='b93a52e2-f010-419f-a4e1-307bd590dfc6'] {
             display: grid; 
             grid-template-columns: 37.060546875rem 25.87890625rem 37.060546875rem;
             grid-template-rows: minmax(16.1865234375rem, max-content) minmax(3.7109375rem, max-content) minmax(3.125rem, max-content);
          }
[id='2892ee6c-34ca-499a-ab6c-f1fe9e05fa91']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(16rem, 12px),1.5625rem);
          }
}
@media (min-width: 480.05px) and (max-width: 768px){
[id='b93a52e2-f010-419f-a4e1-307bd590dfc6'] {
             display: grid; 
             grid-template-columns: 32.74739583333333rem 34.505208333333336rem 32.74739583333333rem;
             grid-template-rows: minmax(21.58203125rem, max-content) minmax(4.947916666666667rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='2892ee6c-34ca-499a-ab6c-f1fe9e05fa91']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(16rem, 12px),2.0833333333333335rem);
          }
}
@media (min-width: 375.05px) and (max-width: 480px){
[id='b93a52e2-f010-419f-a4e1-307bd590dfc6'] {
             display: grid; 
             grid-template-columns: 22.395833333333332rem 55.208333333333336rem 22.395833333333332rem;
             grid-template-rows: minmax(34.53125rem, max-content) minmax(7.916666666666667rem, max-content) minmax(5rem, max-content);
          }
[id='2892ee6c-34ca-499a-ab6c-f1fe9e05fa91']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(16rem, 12px),3.3333333333333335rem);
          }
}
@media (min-width: 0px) and (max-width: 375px){
[id='b93a52e2-f010-419f-a4e1-307bd590dfc6'] {
             display: grid; 
             grid-template-columns: 6.4rem 87.2rem 6.4rem;
             grid-template-rows: minmax(44.2rem, max-content) minmax(12.504150943396226rem, max-content) minmax(6.4rem, max-content);
          }
[id='2892ee6c-34ca-499a-ab6c-f1fe9e05fa91']{
          grid-area: 2/2/3/3;
          font-size: Max(Min(16rem, 12px),5.264905660377358rem);
          }
}
</style>
<template>
  <div>
    <h1>MixGas01</h1>
    <SubTabMenu01 />
    {{Dil_O2_Val}}
  </div>
</template>

<script>
export default{
    data() {
        return{
            Dil_O2_Val: 21,
            Dil_N2_Val: 78,
            Dil_He_Val,
            Bailout_O2_Val,
            Bailout_N2_Val,
            Bailout_He_Val,
            Set_DEPTH_Val,
            Set_END_Val,
            Setpoint_Val,
        }
    },
    computed: {
      //수심에 대한 절대압
      depAta_Cal() {
        return 'depAta_Cal';
      },
      //END에 대한 절대값
      endAta_Cal() {
        return 'endAta_Cal';
      },
      //산소 부분압
      ppO2_Cal() {
        return 'pO2Cal';
      },
      //산소 비율
      fO2_Cal() {
        return 'fO2_Cal';
      },
      //질소 부분압
      ppN2_Cal() {
        return 'ppN2_Cal';
      },
      //질소 비율
      fN2_Cal() {
        return 'fN2_Cal';
      },
      //헬륨 부분압
      ppHe_Cal() {
        return 'ppHe_Cal';
      },
      //헬륨 비율
      fHe_Cal() {
        return 'fHe_Cal';
      }

    },
    methods: {
        
    }
}
</script>

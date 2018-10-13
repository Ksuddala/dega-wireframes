<template>
  <v-layout row>
    <v-flex xs12 sm6 offset-sm3>
      <v-card>
        <v-img
          src="https://i1.wp.com/factly.in/wp-content/uploads/2018/09/Petrol-Diesel-share-in-SoTR-up-to-2017-18.png?w=1404&ssl=1.jpg"
          height="400px"
        >
        </v-img>

        <v-card-title primary-title>
          <div>
            <div class="headline"> Who benefitted from increase in taxes on Petrol & Diesel?
</div>
            <span class="grey--text">By Rakesh Dubbudu on September 14, 2018 </span>
          </div>
        </v-card-title>

        <v-card-actions>
          
          <v-spacer></v-spacer>
          <v-btn icon @click="show = !show">
            <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
          </v-btn>
        </v-card-actions>

        <v-slide-y-transition>
          <v-card-text v-show="show">
        In the last few weeks, there has been an unending debate about petrol & diesel prices. Apart from the increase in global crude oil prices & depreciation of the rupee, increase in taxes has also contributed to higher prices. Both the Central Government & various State Governments increased taxes on petrol & diesel. But who benefitted the most from the increase?
<v-spacer></v-spacer>
Share of Excise duty on Petrol & Diesel in GoI’s tax revenue increased substantially
The Central Excise Duty on Petrol increased from Rs 9.48 per liter to a high of Rs 21.48 per liter. In October 2017, the excise duty on Petrol was reduced by Rs 2 per liter, the first such reduction by the BJP government.  On the other hand, the duty on Diesel increased by more than 4 times from Rs 3.56 per liter to a high Rs 17.33 per liter. Like Petrol, the duty was reduced by Rs 2 per liter in October 2017 to Rs 15.33 per liter.

<v-spacer></v-spacer>

Share of Excise duty on Petrol & Diesel in GoI’s tax revenue increased substantially
The Central Excise Duty on Petrol increased from Rs 9.48 per liter to a high of Rs 21.48 per liter. In October 2017, the excise duty on Petrol was reduced by Rs 2 per liter, the first such reduction by the BJP government.  On the other hand, the duty on Diesel increased by more than 4 times from Rs 3.56 per liter to a high Rs 17.33 per liter. Like Petrol, the duty was reduced by Rs 2 per liter in October 2017 to Rs 15.33 per liter.

<v-spacer></v-spacer>

Even more pronounced is the share of excise duty on petrol & diesel in the central government’s total tax revenue. From just 8% in 2014-15, this share went up to a high of 14.1% in 2016-17. In other words, almost 1 out of every 7 rupees of tax collected by the central government in 2016-17 came from Petrol & Diesel. The share went down to 11.8% in 2017-18 on account of the slight reduction in excise duty. Even then, the share in 2017-18 is almost 50% more than the share in 2014-15.
What about State Governments?
The State VAT on petrol is at least 25% in 21 states with the highest in Mumbai at 39.12%. The State VAT on diesel is more than 20% in 14 states and highest of 28.08% in Andhra Pradesh.
Between 2014-15 & 2017-18, the State Government revenue through VAT/Sales tax on petrol & diesel increased by more than 38%. Though tax rates have increased, the increase in revenue was not proportional because, in most states, the VAT/Sales tax on petrol & diesel is a percentage unlike the fixed amount of central excise duty.  Hence a decrease in crude rates fetched a lower tax to the state governments and an increase fetched higher taxes.

Unlike in the case of central government, the share of VAT/Sales tax on petrol & diesel in State Government’s own tax revenue (SOTR) has remained more or less constant at around 17% in the last 4 years. This figure includes the revenue of all state governments including those in Delhi & Puducherry. Even in terms of the number of states where the share of VAT/Sales tax on petrol & diesel was more than 15% of SOTR, there was only a marginal increase from 19 states in 2014-15 to 21 states in 2017-18.
Who benefitted the most?
Though the revenue of both the central & state governments increased on account of increase in taxes on petrol & diesel, the increase was more prominent in the case of the central government. This is primarily because of the fixed amount of excise duty irrespective of the price of crude oil. On the other hand, the VAT/Sales tax in many states was a percentage on the amount obtained after including excise duty & dealer commission. Hence a decrease in crude price resulted in lower tax amount for states.

          </v-card-text>
        </v-slide-y-transition> 
        </v-slide-y-transition>
      </v-card>
    </v-flex>
  </v-layout>

  
</template>

<script>
  export default {
    layout: 'RestPages',
    data: () => ({
      show: false
    })
  }
</script>
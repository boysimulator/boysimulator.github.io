---
layout: page
title: SLP
permalink: /professional_projects/slp_dcr/
---

Project GitHub repository at [https://github.com/boysimulator/batt-dcr-targets](https://github.com/boysimulator/batt-dcr-targets)

Initialize dictionary data type and execute a print statement to the terminal:

{% highlight ruby %}
d = {}
print()
{% endhighlight %}

Add data to dictionary structure:

{% highlight ruby %}
#Cathode Design
d['cat_active_percent'] = 0.97 #%
d['cat_chg_s_cap'] = 214.33 #mAh/g
d['cat_dchg_s_cap'] = 179.69 #mAh/g
d['cat_density_targ'] = 3.42 #g/cc

#Anode Design
d['an_active_percent'] = 0.948 #%
d['an_chg_s_cap'] = 386 #mAh/g
d['an_dchg_s_cap'] = 337 #mAh/g
d['an_density_targ'] = 1.7 #g/cc

#Cell Design
d['ac_ratio'] = 1.04

#Cell Program Requirements
d['capacity_target'] = 78 #Ah
d['cell_thickness_target'] = 8.5 #mm
d['cell_DCR_target'] = 1.35 #mOhm

#Empirical Data/Properties
d['cat_swelling'] = 1.06
d['an_swelling'] = 1.210
d['DCR_a_coefficient'] = 0.0006 #DCR = ax2+bx+c
d['DCR_b_coefficient'] = -0.0401 #DCR = ax2+bx+c
d['DCR_c_coefficient'] = 1.9773 #DCR = ax2+bx+c
d['large_cell_DCR_factor'] = 1

#Product-Level Cell Componentry
d['al_foil_length'] = 497 #mm
d['al_foil_width'] = 95 #mm
d['al_foil_thickness'] = 12 #um
d['al_tab_length'] = 45 #mm
d['al_tab_width'] = 45 #mm
d['al_tab_thickness'] = 0.4 #mm
d['cu_foil_length'] = 501.5 #mm
d['cu_foil_width'] = 98 #mm
d['cu_foil_thickness'] = 6 #um
d['cu_tab_length'] = 45 #mm
d['cu_tab_width'] = 45 #mm
d['cu_tab_thickness'] = 0.3 #mm
d['pouch_thickness'] = 153 #um
d['separator_thickness'] = 17 #um

#Research-Level Cell Componentry
d['SLP_al_foil_length'] = 44 #mm
d['SLP_al_foil_width']= 30.4 #mm
d['SLP_al_foil_thickness'] = 20 #um
d['SLP_al_tab_length'] = 26 #mm
d['SLP_al_tab_width'] = 10 #mm
d['SLP_al_tab_thickness'] = 0.098 #mm
d['SLP_cu_foil_length'] = 46 #mm
d['SLP_cu_foil_width'] = 32.4 #mm
d['SLP_cu_foil_thickness'] = 6 #um
d['SLP_ni_tab_length'] = 26 #mm
d['SLP_ni_tab_width'] = 10 #mm
d['SLP_ni_tab_thickness'] = 0.1 #mm

#Physical Quantities
d['al_resistivity'] = 0.0000029 #ohm-cm
d['cu_resistivity'] = .00000172 #ohm-cm
d['ni_resistivity'] = 0.00000699 #ohm-cm
{% endhighlight %}

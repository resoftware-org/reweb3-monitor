<!--
/**
 * This file is part of dHealth Wallet Plugins shared under LGPL-3.0
 * Copyright (C) 2021 Using Blockchain Ltd, Reg No.: 12658136, United Kingdom
 *
 * @package     dHealth Wallet Plugins
 * @subpackage  NodeMonitor
 * @author      Grégory Saive for Using Blockchain Ltd <greg@ubc.digital>
 * @license     LGPL-3.0
 */
-->
<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    xmlns:svg="http://www.w3.org/2000/svg"
    viewBox="0 0 64 64"
    version="1.0"
  >
    <defs id="defs2162">
      <radialGradient id="radialGradient2201" gradientUnits="userSpaceOnUse" cy="15.163" cx="15.891" r="27.545">
        <stop id="stop3145" stop-color="#fff" offset="0"/>
        <stop id="stop3147" stop-color="#00f038" stop-opacity="0" offset="1"/>
      </radialGradient>
      <radialGradient id="radialGradient2203" gradientUnits="userSpaceOnUse" cy="16.847" cx="16.028" gradientTransform="matrix(.91888 .94532 -.71707 .69701 13.381 -10.047)" r="27.545">
        <stop id="stop3203" stop-color="#ff9b9b" offset="0"/>
        <stop id="stop3205" stop-color="#f00000" offset="1"/>
      </radialGradient>
    </defs>
    <g id="layer1">
      <g id="g2184" transform="translate(-59.5 -.5)">
        <path id="path3185" d="m55.091 27.727a27.545 27.545 0 1 1 -55.091 0 27.545 27.545 0 1 1 55.091 0z" fill="url(#radialGradient2201)" transform="matrix(.99849 0 0 .99849 63.996 4.8147)"/>
        <path id="path3187" stroke-linejoin="round" d="m55.091 27.727a27.545 27.545 0 1 1 -55.091 0 27.545 27.545 0 1 1 55.091 0z" transform="matrix(.99849 0 0 .99849 63.996 4.8147)" stroke="#be0000" stroke-linecap="round" stroke-width="2.5038" fill="url(#radialGradient2203)"/>
        <path id="path3207" d="m95.594 19.312c-1.798 1.551-3.145 4.37-4.532 5.844-2.631-2.177-3.818-6.236-6.656-7.375-3.44 0.919-8.904 4.136-4.875 7.625 2.058 3.043 6.195 5.747 7.157 8.906-1.468 3.79-4.292 6.616-7.032 9.376 1.34 4.675 7.755 0.524 10.344-1.75 2.065-4.634 3.568 0.898 5.499 2.891 1.541 6.222 9.801 4.403 10.521-0.74-2.84-4.549-6.781-8.924-9.52-13.401 1.085-4.655 5.63-7.771 6.69-12.282-1.79-3.122-5.284 0.353-7.596 0.906z" fill="#fff"/>
      </g>
    </g>
  </svg>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class IconError extends Vue {}
</script>


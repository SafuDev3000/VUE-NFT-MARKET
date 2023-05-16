<template>
  <div>
    <h2>Your NFTs</h2>
    <ul>
      <li v-for="nft in nfts" :key="nft.id">
        {{ nft.name }}
      </li>
    </ul>
  </div>
</template>

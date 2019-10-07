<template>
  <div class="container">
    <el-container>
      <el-aside width="80px">
        <app-aside />
      </el-aside>
      <el-container>
        <el-header style="height:100px">
          <app-header />
        </el-header>
        <el-main>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla culpa amet dolores perspiciatis ad explicabo minima doloremque similique, corrupti expedita ratione aut quia deserunt delectus facere eveniet iste nam veniam aliquid at. Alias adipisci, voluptates totam dolor quia ipsam. Explicabo eius laborum quas nulla dolor quia perspiciatis porro aliquam tempora, quae provident quaerat itaque adipisci voluptatibus veniam quisquam, iure eaque necessitatibus. Cumque nihil odit illo ducimus quisquam ipsam distinctio! Nesciunt quaerat incidunt eos aliquam dolores sunt, veniam, ut molestias eligendi fugiat dolorum sed vero nobis assumenda? Mollitia ab amet, velit error quibusdam fugit doloribus explicabo. Beatae facilis labore consectetur maiores iste necessitatibus culpa mollitia quis minus ad inventore similique ex amet minima rem porro blanditiis saepe nemo possimus reprehenderit omnis est, asperiores dignissimos? Adipisci obcaecati consequuntur nam debitis, voluptate neque? Commodi sapiente rerum molestiae earum expedita voluptas excepturi laborum, distinctio blanditiis cumque itaque doloremque ducimus omnis magni incidunt in praesentium? Nemo dignissimos, laboriosam veritatis corrupti alias facere pariatur est quisquam explicabo, architecto aut repudiandae voluptatum quod voluptates sit corporis culpa adipisci voluptatem voluptas consequuntur? Laborum reiciendis amet quam laboriosam aperiam aut ab unde ratione deleniti, voluptas natus et? Culpa incidunt voluptatibus libero maxime ut laboriosam pariatur modi. Et esse provident repellat pariatur labore voluptate libero ex eligendi sit, quos quod iure expedita doloremque cupiditate nostrum, sapiente beatae, nam maiores ipsum ratione aspernatur distinctio. Dolores praesentium aliquid doloremque officiis voluptas! Quas, odio. Quos, sit quia! Quisquam voluptas assumenda non, pariatur incidunt unde, eveniet reiciendis odit modi iure commodi. Ratione nulla molestiae, unde inventore dolorem minima asperiores debitis culpa eius nemo expedita repellendus, non quisquam assumenda sapiente hic adipisci totam consequatur provident atque dolore qui consequuntur in! Maiores pariatur suscipit explicabo dolore cupiditate vel, laboriosam quidem ex ullam officiis omnis quas, iste ad expedita aspernatur culpa ipsa ut quaerat tenetur sint necessitatibus nam voluptas temporibus minus. Voluptatum repellat doloribus ducimus officia commodi inventore repudiandae voluptas, laudantium at vitae ipsum amet nobis dolor blanditiis excepturi iste quia repellendus reprehenderit! Odio neque est maiores excepturi in, porro, quis doloremque nihil eveniet, laborum quibusdam autem ratione deleniti error delectus voluptatum amet quam! Aspernatur eveniet voluptatum iure quas fuga quidem illo nemo? Dolor nihil voluptas accusantium ipsam, doloremque dolore eius dicta amet minima facere deleniti aliquid praesentium ab, culpa cupiditate doloribus repudiandae harum quo sunt. Enim, aspernatur. Quo sit rerum nihil vero modi at eum alias suscipit, hic veritatis in illum dolorem quae error ullam voluptatibus enim iure, perspiciatis ab aut facilis similique quasi blanditiis? Earum itaque quis magni aliquam amet iusto. Totam aspernatur minima corporis dolores quibusdam ex nobis dolorem porro debitis rem. Reprehenderit facere reiciendis, totam enim accusamus rerum distinctio autem ipsa sint quam dolorem pariatur nostrum corporis aliquam nesciunt saepe repudiandae magni excepturi quos animi magnam ipsam, natus maxime quisquam. Corrupti obcaecati sapiente ullam quam! Sunt rem placeat mollitia consequatur autem? Ipsa officia nulla nisi culpa provident, beatae numquam, voluptatum delectus voluptatem ducimus pariatur ipsum? Molestias, aliquam perspiciatis recusandae quas sequi nam alias ipsum ducimus totam modi labore commodi omnis nostrum soluta eius.</el-main>
        <el-footer style="height:'402px'">
          <app-footer />
        </el-footer>
      </el-container>
    </el-container>
  </div>
</template>

<script>
import AppAside from "~/components/Aside";
import AppHeader from "~/components/Header";
import AppFooter from "~/components/Footer";
export default {
  components: {
    AppAside,
    AppHeader,
    AppFooter
  }
};
</script>

<style>
.el-header,
.el-footer {
  background-color: #eeeeee;
  color: #333;
  text-align: center;
  padding: 0;
}

.el-aside {
  background-color: #ffffff;
  color: #333;
  text-align: center;
}

.el-main {
  background-color: #eeeeee;
  color: #333;
  text-align: center;
}

body > .el-container {
  margin-bottom: 40px;
}
</style>

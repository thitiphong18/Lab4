<script setup lang="ts"></script>
<script>
export default {
  data: () => ({
    colors: ["green", "purple", "orange", "indigo", "red"],
    rating: 4.5,
  }),
};
</script>
<template>
  <v-container>
    <v-row>
      <v-col>
        <v-card max-width="1400" class="mx-auto">
          <v-layout>
            <v-app-bar color="info" density="prominent">
              <v-app-bar-title><h1>Portfolio</h1></v-app-bar-title>

              <template v-slot:append> </template>
            </v-app-bar>

            <v-main>
              <v-container fluid>
                <v-card
                  border
                  class="mb-2"
                  density="compact"
                  prepend-avatar="https://scontent.fbkk2-4.fna.fbcdn.net/v/t39.30808-6/314609315_10225456965549690_5287212767421642758_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=730e14&_nc_eui2=AeEU6zZYocwmxoP-nxC5Sh1EJaIkumxu-xIloiS6bG77EtkrneAOFqD7Dh6xbXRc1XY&_nc_ohc=g5MaLRt3dp0AX9dtnpB&_nc_zt=23&_nc_ht=scontent.fbkk2-4.fna&oh=00_AfAdl-RgnNuunV6u4l01MiTbzhm7pnF7ghC1etzbhaQCUA&oe=639F8587"
                  subtitle="ฐิติพงศ์ นิ่มมาก"
                  title="คิวเอง"
                  variant="text"
                >
                  <v-img
                    src="https://scontent.fbkk2-4.fna.fbcdn.net/v/t39.30808-6/314609315_10225456965549690_5287212767421642758_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=730e14&_nc_eui2=AeEU6zZYocwmxoP-nxC5Sh1EJaIkumxu-xIloiS6bG77EtkrneAOFqD7Dh6xbXRc1XY&_nc_ohc=g5MaLRt3dp0AX9dtnpB&_nc_zt=23&_nc_ht=scontent.fbkk2-4.fna&oh=00_AfAdl-RgnNuunV6u4l01MiTbzhm7pnF7ghC1etzbhaQCUA&oe=639F8587"
                    style="height: 70%"
                    height="900"
                    cover
                  ></v-img>

                  <v-card-text>
                    <h2>ประวัติส่วนตัว</h2>

                    สวัสดีครับ ผมนาย ฐิติพงศ์ นิ่มมาก ชื่อเล่น คิว เกิดวันที่ 17
                    กรกฎาคม พ.ศ.2545 เกิดที่ กรุงเทพมหานคร สิ่งที่ชอบ เธอ
                    ปัจจุบันเป็นนักศึกษาของมหาวิทยาลัย บูรพา
                  </v-card-text>
                </v-card>

                <v-card
                  border
                  density="comfortable"
                  prepend-avatar="https://scontent.fbkk2-4.fna.fbcdn.net/v/t39.30808-6/314609315_10225456965549690_5287212767421642758_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=730e14&_nc_eui2=AeEU6zZYocwmxoP-nxC5Sh1EJaIkumxu-xIloiS6bG77EtkrneAOFqD7Dh6xbXRc1XY&_nc_ohc=g5MaLRt3dp0AX9dtnpB&_nc_zt=23&_nc_ht=scontent.fbkk2-4.fna&oh=00_AfAdl-RgnNuunV6u4l01MiTbzhm7pnF7ghC1etzbhaQCUA&oe=639F8587"
                  subtitle="ฐิติพงศ์ นิ่มมาก"
                  title="คิวเอง"
                  variant="text"
                >
                  <v-img
                    src="https://3.bp.blogspot.com/-TaaXpdtoZn4/XGoS6IlEslI/AAAAAAAAFt8/nVeUdicR3XEZABmEDu18vQq6eAgI1HU6QCLcBGAs/s640/IMG_20190130_071240.jpg"
                    height="800"
                    cover
                  ></v-img>

                  <v-card-text>
                    <h2>ประวัติการศึกษาระดับประธมศึกษา</h2>
                    ชั้นประธมศึกษา ศึกษาที่โรงเรียน อนุบาลวัดคลองใหญ่ ตำบล
                    คลองใหญ่ อำเภอ คลองใหญ่ จังหวัด ตราด ก่อตั้ง ปี 2466
                  </v-card-text>
                </v-card>

                <v-card
                  border
                  density="comfortable"
                  prepend-avatar="https://scontent.fbkk2-4.fna.fbcdn.net/v/t39.30808-6/314609315_10225456965549690_5287212767421642758_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=730e14&_nc_eui2=AeEU6zZYocwmxoP-nxC5Sh1EJaIkumxu-xIloiS6bG77EtkrneAOFqD7Dh6xbXRc1XY&_nc_ohc=g5MaLRt3dp0AX9dtnpB&_nc_zt=23&_nc_ht=scontent.fbkk2-4.fna&oh=00_AfAdl-RgnNuunV6u4l01MiTbzhm7pnF7ghC1etzbhaQCUA&oe=639F8587"
                  subtitle="ฐิติพงศ์ นิ่มมาก"
                  title="คิวเอง"
                  variant="text"
                >
                  <v-img
                    src="https://www.matichon.co.th/wp-content/uploads/2017/06/93-1-728x450.jpg"
                    height="800"
                    cover
                  ></v-img>

                  <v-card-text>
                    <h2>ประวัติการศึกษาระดับมัธยมศึกษา</h2>
                    ชั้นมัธยยมศึกษาทั้งตอนต้นและต้อนปลาย ศึกษาที่โรงเรียน
                    ตราษตระการคุณ ตำบล วังกระแจะ อำเภอ เมือง จังหวัด ตราด
                    ก่อตั้ง 14 มกราคม พ.ศ. 2442
                  </v-card-text>
                </v-card>
                <v-card
                  border
                  density="comfortable"
                  prepend-avatar="https://scontent.fbkk2-4.fna.fbcdn.net/v/t39.30808-6/314609315_10225456965549690_5287212767421642758_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=730e14&_nc_eui2=AeEU6zZYocwmxoP-nxC5Sh1EJaIkumxu-xIloiS6bG77EtkrneAOFqD7Dh6xbXRc1XY&_nc_ohc=g5MaLRt3dp0AX9dtnpB&_nc_zt=23&_nc_ht=scontent.fbkk2-4.fna&oh=00_AfAdl-RgnNuunV6u4l01MiTbzhm7pnF7ghC1etzbhaQCUA&oe=639F8587"
                  subtitle="ฐิติพงศ์ นิ่มมาก"
                  title="คิวเอง"
                  variant="text"
                >
                  <v-img
                    src="https://sites.google.com/site/9mhalayrathbalthinareiyn/_/rsrc/1486175274059/mhawithyalay-burpha/slider4.jpg"
                    height="600"
                    cover
                  ></v-img>

                  <v-card-text>
                    <h2>ประวัติการศึกษาระดับอุดมศึกษา</h2>
                    ระดับอุดมศึกษา ศึกษาที่มหาวิทยาลัยบูรพา 169 ถ.ลงหาดบางแสน
                    ต.แสนสุข อ.เมือง จ.ชลบุรี 20131. ก่อตั้ง 8 กรกฎาคม 2498
                  </v-card-text>
                </v-card>
              </v-container>
            </v-main>
          </v-layout>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

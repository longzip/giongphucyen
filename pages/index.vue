<template>
  <div>
    <navbar-component></navbar-component>
    <main>
      <div
        class="
          relative
          pt-16
          pb-32
          flex
          content-center
          items-center
          justify-center
        "
        style="min-height: 75vh"
      >
        <div
          class="absolute top-0 w-full h-full bg-center bg-cover"
          style="background-image: url('/images/giong-phuc-yen')"
        >
          <span
            id="blackOverlay"
            class="w-full h-full absolute opacity-75 bg-black"
          ></span>
        </div>
        <div class="container relative mx-auto">
          <div class="items-center flex flex-wrap">
            <div class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center">
              <div class="pr-12">
                <h1 class="text-white font-semibold text-5xl">
                  Trung tâm tiêm chủng Gióng Phúc Yên.
                </h1>
                <p class="mt-4 text-lg text-gray-300">
                  Cung cấp các dịch vụ tiêm chủng chất lượng, đáp ứng nhu cầu
                  của người dân trên địa bàn thành phố Phúc Yên và các vùng lân
                  cận được sử dụng dịch vụ tiêm chủng đạt tiêu chuẩn quốc tế
                  theo quy định của Bộ Y tế.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div
          class="
            top-auto
            bottom-0
            left-0
            right-0
            w-full
            absolute
            pointer-events-none
            overflow-hidden
          "
          style="height: 70px"
        >
          <svg
            class="absolute bottom-0 overflow-hidden"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="none"
            version="1.1"
            viewBox="0 0 2560 100"
            x="0"
            y="0"
          >
            <polygon
              class="text-gray-300 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
      </div>
      <section class="pb-20 bg-gray-300 -mt-24">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap">
            <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="
                  relative
                  flex flex-col
                  min-w-0
                  break-words
                  bg-white
                  w-full
                  mb-8
                  shadow-lg
                  rounded-lg
                "
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="
                      text-white
                      p-3
                      text-center
                      inline-flex
                      items-center
                      justify-center
                      w-12
                      h-12
                      mb-5
                      shadow-lg
                      rounded-full
                      bg-red-400
                    "
                  >
                    <i class="fas fa-award"></i>
                  </div>
                  <h6 class="text-xl font-semibold">Đạt tiêu chuẩn GSP</h6>
                  <p class="mt-2 mb-4 text-gray-600">
                    Trung tâm tiêm chủng Gióng Phúc Yên được đầu tư cơ sở vật
                    chất khang trang, sạch sẽ, tiện nghi cao cấp, điều kiện bảo
                    quản vắc xin được đảm bảo theo tiêu chuẩn GSP, đúng tiêu
                    chuẩn quốc tế.
                  </p>
                </div>
              </div>
            </div>
            <div class="w-full md:w-4/12 px-4 text-center">
              <div
                class="
                  relative
                  flex flex-col
                  min-w-0
                  break-words
                  bg-white
                  w-full
                  mb-8
                  shadow-lg
                  rounded-lg
                "
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="
                      text-white
                      p-3
                      text-center
                      inline-flex
                      items-center
                      justify-center
                      w-12
                      h-12
                      mb-5
                      shadow-lg
                      rounded-full
                      bg-blue-400
                    "
                  >
                    <i class="fas fa-retweet"></i>
                  </div>
                  <h6 class="text-xl font-semibold">Đầy đủ các loại Vắc xin</h6>
                  <p class="mt-2 mb-4 text-gray-600">
                    Trung tâm tiêm chủng Gióng còn cung cấp đầy đủ các loại vắc
                    xin dành cho trẻ em và người lớn đang được người dân quan
                    tâm như: vắc xin 6 trong 1, phế cầu, Rota, cúm, sởi, quai
                    bị, rubella, thủy đậu, viêm não do não mô cầu AC, BC, Viêm
                    não Nhật Bản,...từ các nhà sản xuất vắc xin hàng đầu trên
                    thế giới như: Pháp, Bỉ, Mỹ, Cu Ba, Hàn Quốc, Ba Lan,....
                  </p>
                </div>
              </div>
            </div>
            <div class="pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="
                  relative
                  flex flex-col
                  min-w-0
                  break-words
                  bg-white
                  w-full
                  mb-8
                  shadow-lg
                  rounded-lg
                "
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="
                      text-white
                      p-3
                      text-center
                      inline-flex
                      items-center
                      justify-center
                      w-12
                      h-12
                      mb-5
                      shadow-lg
                      rounded-full
                      bg-green-400
                    "
                  >
                    <i class="fas fa-fingerprint"></i>
                  </div>
                  <h6 class="text-xl font-semibold">
                    Hệ thống tiêm chủng Quốc Gia
                  </h6>
                  <p class="mt-2 mb-4 text-gray-600">
                    Trung tâm tiêm chủng Gióng Phúc Yên có đội ngũ nhân viên
                    nhiều kinh nghiệm, phục vụ chu đáo, nhiệt tình trong quá
                    trình chăm sóc trước, trong và sau tiêm chủng, đảm bảo an
                    toàn. Đặc biệt là các trẻ đến tiêm được khám và tư vấn miễn
                    phí, được cập nhật vào hệ thống tiêm chủng Quốc gia, được
                    nhắn tin nhắc lịch cho mẹ các mũi tiêm tiếp theo
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="flex flex-wrap items-center mt-32">
            <div class="w-full md:w-5/12 px-4 mr-auto ml-auto">
              <div
                class="
                  text-gray-600
                  p-3
                  text-center
                  inline-flex
                  items-center
                  justify-center
                  w-16
                  h-16
                  mb-6
                  shadow-lg
                  rounded-full
                  bg-gray-100
                "
              >
                <i class="fas fa-user-friends text-xl"></i>
              </div>
              <h3 class="text-3xl mb-2 font-semibold leading-normal">
                Về công ty Gióng Việt Nam
              </h3>
              <p
                class="
                  text-lg
                  font-light
                  leading-relaxed
                  mt-4
                  mb-4
                  text-gray-700
                "
              >
                Hệ thống Trung tâm tiêm chủng Gióng Việt Nam bao gồm 4 cơ sở với
                cơ sở vật chất, nhân lực đầy đủ, điều kiện bảo quản vắc xin đảm
                bảo theo tiêu chuẩn GSP, cung cấp đầy đủ các loại vắc xin (6in1,
                phế cầu, Rota, cúm, sởi - quai bị - rubella, thủy đậu, viêm não
                do não mô cầu AC, BC, viêm não Nhật Bản,...từ các nước Pháp, Bỉ,
                Hà Lan, Mỹ, Canada,...) phục vụ nhu cầu phòng bệnh cho trẻ em và
                người lớn!
              </p>
              <p
                class="
                  text-lg
                  font-light
                  leading-relaxed
                  mt-0
                  mb-4
                  text-gray-700
                "
              >
                Đến với Hệ thống Trung tâm tiêm chủng Gióng Việt Nam, quý khách
                được cung cấp các dịch vụ tiêm phòng đầy đủ, phòng tiêm đạt tiêu
                chuẩn, đội ngũ nhân viên có kinh nghiệm, phục vụ chu đáo, nhiệt
                tình, chăm sóc trước tiêm, trong quá trình tiêm và sau tiêm,
                được đảm bảo an toàn, hài lòng. Đặc biệt là các bé đến tiêm được
                khám và tư vấn miễn phí, được cập nhật vào hệ thống tiêm chủng
                Quốc gia, bố mẹ bé được nhắn tin nhắc lịch các mũi tiếp theo.
              </p>
              <a
                href="https://goo.gl/maps/bmDLHKiggHmSZWeR6"
                class="font-bold text-gray-800 mt-8"
                >Xem địa chỉ trung tâm</a
              >
            </div>
            <div class="w-full md:w-4/12 px-4 mr-auto ml-auto">
              <div
                class="
                  relative
                  flex flex-col
                  min-w-0
                  break-words
                  w-full
                  mb-6
                  shadow-lg
                  rounded-lg
                  bg-pink-600
                "
              >
                <img
                  alt="Trung tâm tiêm chủng vắc xin gióng phúc yên"
                  src="/images/tiem-chung-vac-xin-giong"
                  class="w-full align-middle rounded-t-lg"
                />
                <blockquote class="relative p-8 mb-4">
                  <svg
                    preserveAspectRatio="none"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 583 95"
                    class="absolute left-0 w-full block"
                    style="height: 95px; top: -94px"
                  >
                    <polygon
                      points="-30,95 583,95 583,65"
                      class="text-pink-600 fill-current"
                    ></polygon>
                  </svg>
                  <h4 class="text-xl font-bold text-white">
                    Dịch vụ tiêm chủng
                  </h4>
                  <p class="text-md font-light mt-2 text-white">
                    Ngoài cung cấp dịch vụ tiêm chủng cho các cá nhân, gia đình,
                    Hệ thống Trung tâm tiêm chủng Gióng Việt Nam còn cung cấp
                    dịch vụ tiêm chủng tại các cơ quan, doanh nghiệp
                  </p>
                </blockquote>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="relative py-20">
        <div
          class="
            bottom-auto
            top-0
            left-0
            right-0
            w-full
            absolute
            pointer-events-none
            overflow-hidden
            -mt-20
          "
          style="height: 80px"
        >
          <svg
            class="absolute bottom-0 overflow-hidden"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="none"
            version="1.1"
            viewBox="0 0 2560 100"
            x="0"
            y="0"
          >
            <polygon
              class="text-white fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
        <div class="container mx-auto px-4">
          <div class="items-center flex flex-wrap">
            <div class="w-full md:w-4/12 ml-auto mr-auto px-4">
              <img
                alt="..."
                class="max-w-full rounded-lg shadow-lg"
                src="https://images.unsplash.com/photo-1555212697-194d092e3b8f?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=634&amp;q=80"
              />
            </div>
            <div class="w-full md:w-5/12 ml-auto mr-auto px-4">
              <div class="md:pr-12">
                <div
                  class="
                    text-pink-600
                    p-3
                    text-center
                    inline-flex
                    items-center
                    justify-center
                    w-16
                    h-16
                    mb-6
                    shadow-lg
                    rounded-full
                    bg-pink-300
                  "
                >
                  <i class="fas fa-rocket text-xl"></i>
                </div>
                <h3 class="text-3xl font-semibold">Dịch vụ tiêm chủng</h3>
                <p class="mt-4 text-lg leading-relaxed text-gray-600">
                  Tại Trung tâm tiêm chủng Gióng Phúc Yên, ngoài dịch vụ tiêm
                  chủng trọn gói, chúng tôi còn có dịch vụ tiêm chủng theo yêu
                  cầu của Quý khách hàng như tiêm chủng cho cá nhân, tiêm chủng
                  cho Quý cơ quan, doanh nghiệp, trường học. Khách hàng có thể
                  đăng ký đặt giữ vắc xin theo yêu cầu để được tiêm đúng loại
                  vắc xin, đúng lịch và đúng giá.
                </p>
                <ul class="list-none mt-6">
                  <li class="py-2">
                    <div class="flex items-center">
                      <div>
                        <span
                          class="
                            text-xs
                            font-semibold
                            inline-block
                            py-1
                            px-2
                            uppercase
                            rounded-full
                            text-pink-600
                            bg-pink-200
                            mr-3
                          "
                          ><i class="fas fa-fingerprint"></i
                        ></span>
                      </div>
                      <div>
                        <h4 class="text-gray-600">Tiêm chủng theo yêu cầu</h4>
                      </div>
                    </div>
                  </li>
                  <li class="py-2">
                    <div class="flex items-center">
                      <div>
                        <span
                          class="
                            text-xs
                            font-semibold
                            inline-block
                            py-1
                            px-2
                            uppercase
                            rounded-full
                            text-pink-600
                            bg-pink-200
                            mr-3
                          "
                          ><i class="fab fa-html5"></i
                        ></span>
                      </div>
                      <div>
                        <h4 class="text-gray-600">
                          Tiêm cho người chuẩn bị mang thai
                        </h4>
                      </div>
                    </div>
                  </li>
                  <li class="py-2">
                    <div class="flex items-center">
                      <div>
                        <span
                          class="
                            text-xs
                            font-semibold
                            inline-block
                            py-1
                            px-2
                            uppercase
                            rounded-full
                            text-pink-600
                            bg-pink-200
                            mr-3
                          "
                          ><i class="far fa-paper-plane"></i
                        ></span>
                      </div>
                      <div>
                        <h4 class="text-gray-600">
                          Tiêm chọn gói cho người lớn
                        </h4>
                      </div>
                    </div>
                  </li>
                  <li class="py-2">
                    <div class="flex items-center">
                      <div>
                        <span
                          class="
                            text-xs
                            font-semibold
                            inline-block
                            py-1
                            px-2
                            uppercase
                            rounded-full
                            text-pink-600
                            bg-pink-200
                            mr-3
                          "
                          ><i class="far fa-paper-plane"></i
                        ></span>
                      </div>
                      <div>
                        <h4 class="text-gray-600">Tiêm chọn gói cho trẻ em</h4>
                      </div>
                    </div>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="pt-20 pb-48">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap justify-center text-center mb-24">
            <div class="w-full lg:w-6/12 px-4">
              <h2 class="text-4xl font-semibold">Độ ngũ chuyên gia</h2>
              <p class="text-lg leading-relaxed m-4 text-gray-600">
                Đội ngũ chuyên gia giàu kinh nghiệm và tận tâm
              </p>
            </div>
          </div>
          <div class="flex flex-wrap">
            <div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
              <div class="px-6">
                <img
                  alt="Nguyễn Thị Thúy"
                  src="~/assets/img/nguyen-thi-thuy.jpg"
                  class="shadow-lg rounded-full max-w-full mx-auto"
                  style="max-width: 120px"
                />
                <div class="pt-6 text-center">
                  <h5 class="text-xl font-bold">
                    Ths. BS Chuyên Khoa II Nguyễn Thị Thúy
                  </h5>
                  <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                    Nguyên Giám đốc TTYT Q.Long Biên
                  </p>
                </div>
              </div>
            </div>
            <div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
              <div class="px-6">
                <img
                  alt="Đỗ Như Chinh"
                  src="~/assets/img/do-nhu-chinh.jpg"
                  class="shadow-lg rounded-full max-w-full mx-auto"
                  style="max-width: 120px"
                />
                <div class="pt-6 text-center">
                  <h5 class="text-xl font-bold">Ths. BS Đỗ Như Chinh</h5>
                  <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                    Nguyên P.Giám đốc BV Phổi Hà Nội
                  </p>
                </div>
              </div>
            </div>
            <div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
              <div class="px-6">
                <img
                  alt="Đào Hồng Chinh"
                  src="~/assets/img/dao-hong-chinh.jpg"
                  class="shadow-lg rounded-full max-w-full mx-auto"
                  style="max-width: 120px"
                />
                <div class="pt-6 text-center">
                  <h5 class="text-xl font-bold">Ths. BS Đào Hồng Chinh</h5>
                  <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                    Nguyên P.Giám đốc TTYT Q.Long Biên
                  </p>
                </div>
              </div>
            </div>
            <div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
              <div class="px-6">
                <img
                  alt="Phan Ngọc Lan"
                  src="~/assets/img/phan-ngoc-lan.jpg"
                  class="shadow-lg rounded-full max-w-full mx-auto"
                  style="max-width: 120px"
                />
                <div class="pt-6 text-center">
                  <h5 class="text-xl font-bold">Ths. BS Phan Ngọc Lan</h5>
                  <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                    Bác sỹ tư vấn, khám sàng lọc
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="pb-20 relative block bg-gray-900">
        <div
          class="
            bottom-auto
            top-0
            left-0
            right-0
            w-full
            absolute
            pointer-events-none
            overflow-hidden
            -mt-20
          "
          style="height: 80px"
        >
          <svg
            class="absolute bottom-0 overflow-hidden"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="none"
            version="1.1"
            viewBox="0 0 2560 100"
            x="0"
            y="0"
          >
            <polygon
              class="text-gray-900 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
        <div class="container mx-auto px-4 lg:pt-24 lg:pb-64">
          <div class="flex flex-wrap text-center justify-center">
            <div class="w-full lg:w-6/12 px-4">
              <h2 class="text-4xl font-semibold text-white">
                Đặt lịch tiêm chủng
              </h2>
              <p class="text-lg leading-relaxed mt-4 mb-4 text-gray-500">
                Việc đăng ký thông tin tiêm chủng nhằm giúp Quý Khách tiết kiệm
                thời gian khi làm thủ tục tại quầy lễ tân của Trung Tâm, không
                mang ý nghĩa đặt trước giữ mũi vắc xin
              </p>
            </div>
          </div>
        </div>
      </section>
      <section class="relative block py-24 lg:pt-0 bg-gray-900">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap justify-center lg:-mt-64 -mt-48">
            <div class="w-full lg:w-6/12 px-4">
              <div
                class="
                  relative
                  flex flex-col
                  min-w-0
                  break-words
                  w-full
                  mb-6
                  shadow-lg
                  rounded-lg
                  bg-gray-300
                "
              >
                <div class="flex-auto p-5 lg:p-10">
                  <h4 class="text-2xl font-semibold">Want to work with us?</h4>
                  <p class="leading-relaxed mt-1 mb-4 text-gray-600">
                    Complete this form and we will get back to you in 24 hours.
                  </p>
                  <div class="relative w-full mb-3 mt-8">
                    <label
                      class="
                        block
                        uppercase
                        text-gray-700 text-xs
                        font-bold
                        mb-2
                      "
                      for="full-name"
                      >Full Name</label
                    ><input
                      type="text"
                      class="
                        border-0
                        px-3
                        py-3
                        placeholder-gray-400
                        text-gray-700
                        bg-white
                        rounded
                        text-sm
                        shadow
                        focus:outline-none focus:ring
                        w-full
                      "
                      placeholder="Full Name"
                      style="transition: all 0.15s ease 0s"
                    />
                  </div>
                  <div class="relative w-full mb-3">
                    <label
                      class="
                        block
                        uppercase
                        text-gray-700 text-xs
                        font-bold
                        mb-2
                      "
                      for="email"
                      >Email</label
                    ><input
                      type="email"
                      class="
                        border-0
                        px-3
                        py-3
                        placeholder-gray-400
                        text-gray-700
                        bg-white
                        rounded
                        text-sm
                        shadow
                        focus:outline-none focus:ring
                        w-full
                      "
                      placeholder="Email"
                      style="transition: all 0.15s ease 0s"
                    />
                  </div>
                  <div class="relative w-full mb-3">
                    <label
                      class="
                        block
                        uppercase
                        text-gray-700 text-xs
                        font-bold
                        mb-2
                      "
                      for="message"
                      >Message</label
                    ><textarea
                      rows="4"
                      cols="80"
                      class="
                        border-0
                        px-3
                        py-3
                        placeholder-gray-400
                        text-gray-700
                        bg-white
                        rounded
                        text-sm
                        shadow
                        focus:outline-none focus:ring
                        w-full
                      "
                      placeholder="Type a message..."
                    ></textarea>
                  </div>
                  <div class="text-center mt-6">
                    <button
                      class="
                        bg-gray-900
                        text-white
                        active:bg-gray-700
                        text-sm
                        font-bold
                        uppercase
                        px-6
                        py-3
                        rounded
                        shadow
                        hover:shadow-lg
                        outline-none
                        focus:outline-none
                        mr-1
                        mb-1
                      "
                      type="button"
                      style="transition: all 0.15s ease 0s"
                    >
                      Send Message
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
    <footer-component></footer-component>
  </div>
</template>
<script>
import NavbarComponent from '@/components/Navbar.vue'
import FooterComponent from '@/components/Footer.vue'
export default {
  components: {
    NavbarComponent,
    FooterComponent,
  },
}
</script>

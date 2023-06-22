<template>
  <div>
    <div class="navbar header py-2">
      <h3 class="text-center text-white font-weight-bold">REMITA SDK PAGE</h3>
</div>

<div class="sidebar">
  <ul>
          <li>OVERVIEW</li>
          <li>ALL SDK AND PLUGINS</li>
          <li>MOBILE SDK</li>
          <li>REACT SDK</li>
          <li>BACKEND SDK</li>
          <li>PLUGINS</li>
          <li>WEB SDK</li>
        </ul>
</div>

<div class="content">
  <div class="overview">
          <div class="container">
            <h1 class="text-center mt-5 font-weight-bolder heading">Overview</h1>
            <p class="mx-5 overview-content">
              Welcome to the Remita SDK and Plugins Page! Here, you will
              discover a comprehensive range of Remita software development kits
              (SDKs) and plugins, designed to enhance your integration
              experience with the Remita payment platform. Our SDKs and plugins
              provide seamless integration solutions, enabling businesses to
              leverage the power of Remita's robust payment infrastructure. <br/><br/>
              Remita is a leading payment gateway in Nigeria, offering a secure,
              reliable, and versatile platform for processing online payments.
              With our SDKs and plugins, developers can easily incorporate
              Remita's payment capabilities into their websites, applications,
              and e-commerce platforms. Whether you're a small business owner,
              an e-commerce entrepreneur, or a large enterprise, our tools are
              tailored to meet your specific needs.<br/><br/> The Remita SDKs offer a
              range of programming libraries and tools that enable developers to
              integrate Remita's payment gateway functionality into their
              applications. Whether you prefer working with Java, Python, PHP,
              or other popular programming languages, our SDKs provide the
              necessary resources to ensure a smooth integration process. From
              processing payments, retrieving transaction history, to generating
              invoices, our SDKs offer a comprehensive set of features that
              allow you to harness the full potential of Remita's payment
              capabilities.<br/><br/> In addition to our SDKs, we offer a collection of
              plugins that can be seamlessly integrated into popular content
              management systems (CMS) and e-commerce platforms. Whether you're
              using WordPress, WooCommerce, Magento, Shopify, or other
              platforms, our plugins provide a hassle-free way to integrate
              Remita's payment gateway into your website. With easy installation
              and configuration options, you can start accepting payments
              through Remita in no time.<br/><br/> Our SDKs and plugins are backed by
              Remita's robust infrastructure, ensuring secure and reliable
              payment processing. We prioritize data security and compliance
              with industry standards, so you can rest assured that your
              customers' sensitive information is protected.<br/><br/> By integrating
              Remita's payment gateway into your website or application, you
              open up a world of possibilities for your business. Accept
              payments from various channels, including debit cards, credit
              cards, bank transfers, and e-wallets. Enjoy real-time transaction
              updates, automated invoicing, and reconciliation. Expand your
              customer base and streamline your payment processes with Remita.<br/><br/>
              Whether you're a developer seeking a powerful SDK or a business
              owner looking for a seamless integration solution, the Remita SDK
              and Plugins Page is your go-to resource. Explore our range of SDKs
              and plugins, discover their respective use cases, and start
              revolutionizing your payment processes with Remita today!
            </p>
          </div>
        </div>
</div>

  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.header {
  background-color: rgb(255, 115, 0);
}
.heading {
  color: rgb(255, 115, 0);
}
ul {
  list-style-type: none;
  text-align: center;
}
li {
  padding: 20px 15px;
  cursor: pointer;
  border-bottom: 2px solid gray;
}
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 50px;
}


.sidebar {
  position: fixed;
  top: 50px;
  left: 0;
  width: 200px;
  height: calc(100% - 50px);
  background-color: #f5f5f5;
}


.content {
  margin-left: 200px; 
  padding: 20px;
}


.content {
  background-color: #fff;
  color: #333;
}


.content h1 {
  margin-top: 0;
}
.overview-content {
  width: 800px;
  text-align: justify;
}
</style>

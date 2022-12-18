<template>
  <div class="firstSection">
    <div class="container">
      <SelectIcon />
      <div class="content">
        <h1 class="title">Content Service</h1>
        <p class="subtitle">
          Flexibler Kostenrechner für transparente kostenabschätzungen
        </p>
      </div>
      <button class="btn">
        <div class="euro">
          <EuroIcon class="euroIcon" />
        </div>
          <p class="btn-title">Zum Rechner</p>
      </button>
    </div>
  </div>
</template>

<script>
import SelectIcon from "@/components/icons/SelectIcon.vue";
import EuroIcon from "@/components/icons/EuroIcon.vue";
export default {
  components: {
    SelectIcon,
    EuroIcon,
  },
};
</script>

<style scoped>
.firstSection {
  background-color: #f6f7f9;
  width: 100%;
  padding: 150px 0px;
  display: flex;
}
.container {
  margin: auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 5px;
}
.content {
  text-align: center;
}
.title {
  font-size: 150px;
  font-weight: 600;
  color: #022B3B;
  line-height: 0px;
  font-family: Inter;
}
.subtitle {
  font-size: 28px;
  font-weight: 400;
  color: #02303b;
  font-family: Inter;
}
.btn {
  background-color: #02303b;
  border: none;
  border-radius: 60px;
  padding: 8px 20px;
  display: flex;
  align-items: center;
  gap: 14px;
  cursor: pointer;
  padding-right: 60px;
}
.btn-title {
  font-size: 20px;
  font-weight: 500;
  color: #F6F7F9;
  font-family: Inter;
}
.euro {
  width: 48px;
  height: 48px;
  border-radius: 100%;
  background-color: #F6F7F9;
  border-radius: 50%;
  display: flex;
}

.euroIcon {
  margin: auto;
}

.btn:hover {
  background-color: #022b3b;
}

/* Responsive */


@media only screen and (max-width: 1174px) {
  .title {
    font-size: 100px;
  }
  .subtitle {
    font-size: 20px;
  }
  .btn {
    padding: 8px 20px;
    padding-right: 40px;
  }
  .btn-title {
    font-size: 16px;
  }
  .euro {
    width: 40px;
    height: 40px;
  }
  .euroIcon {
    width: 20px;
    height: 20px;
  }
}

@media only screen and (max-width: 782px) {
  .title {
    font-size: 60px;
  }
  .subtitle {
    font-size: 18px;
  }
  .btn {
    padding: 8px 20px;
    padding-right: 40px;
  }
  .btn-title {
    font-size: 14px;
  }
  .euro {
    width: 40px;
    height: 40px;
  }
  .euroIcon {
    width: 20px;
    height: 20px;
  }
}

@media only screen and (max-width: 480px) {
  .title {
    font-size: 40px;
    line-height: 48px;
  }
  .subtitle {
    font-size: 16px;
  }
  .btn {
    padding: 8px 20px;
    padding-right: 40px;
  }
  .btn-title {
    font-size: 12px;
  }
  .euro {
    width: 40px;
    height: 40px;
  }
  .euroIcon {
    width: 20px;
    height: 20px;
  }
}

@media only screen and (max-width: 320px) {
  .title {
    font-size: 50px;
  }
  .subtitle {
    font-size: 14px;
  }
  .btn {
    padding: 8px 20px;
    padding-right: 40px;
  }
  .btn-title {
    font-size: 10px;
  }
  .euro {
    width: 40px;
    height: 40px;
  }
  .euroIcon {
    width: 20px;
    height: 20px;
  }
}

</style>

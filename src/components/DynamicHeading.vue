
<script>
import {h} from "vue"

export default {
  render() {
    return h(`h${this.level}`, "Hello Frontend Masters!")
  },
  props: {
    level: {
      type: Number,
      default: 1
    }
  }
}
</script>

<style></style>

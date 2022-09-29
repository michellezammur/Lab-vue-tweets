<script setup>
    import Timestamp from "./Timestamp.vue";
    defineProps({
      user: {
        type: Object,
        default: () => ({
          name: "Snopp Dogg",
          handle: "@Snoopy",
        }),
      },
      timestamp: {
        type: String,
      },
    });
    
    </script>
    
    <template>
    
    
      <!-- Iteration 2 - postRefactoring -->
      <div class="top">
        <span class="name">{{ user.name }}</span>
        <span class="handle">{{ user.handle }}</span>
        <Timestamp v-bind:timestamp="timestamp" />
      </div>
    </template>
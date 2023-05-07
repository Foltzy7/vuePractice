<template>
  <div class="wow">
    <h1>This page contains helpful WoW links</h1>
    <v-expansion-panels multiple>
      <v-expansion-panel title="Evoker" class="evoker-green">
        <v-expansion-panel-text>
          <div class="d-flex flex-column justify-space-between">
            <v-expansion-panels multiple class="mb-3">
              <v-expansion-panel title="Preservation">
                <v-expansion-panel-text>
                  <h3 class="evoker-green">Stat prio</h3>
                  <p>Mythics: Vers=crit>haste>mastery OR mastery>haste>vers>crit</p>
                  <p>Raid: mastery>haste>crit</p>
                  <hr />
                  <h3 class="evoker-green">Raider IO</h3>
                  <div class="ml-3">
                    <ul>
                      <li>
                        <a
                          href="https://raider.io/characters/eu/stormscale/M%C3%A9%C3%B2w#season=season-df-1"
                          target="_blank"
                          class="evoker-green"
                          >Meow
                        </a>
                      </li>
                      <li>
                        <a
                          href="https://raider.io/characters/us/area-52/Dragonfishi#season=season-df-1"
                          target="_blank"
                          class="evoker-green"
                          >Dragonfishi
                        </a>
                      </li>
                    </ul>
                  </div>
                </v-expansion-panel-text>
              </v-expansion-panel>
            </v-expansion-panels>
            <v-divider></v-divider>
            <v-expansion-panels multiple>
              <v-expansion-panel title="Devastation">
                <v-expansion-panel-text>
                  <h3 class="evoker-green">Stat prio</h3>
                  <p>Mythics: mastery>haste>vers>crit</p>
                  <p>Raid: mastery>haste>crit</p>
                  <hr />
                  <h3 class="evoker-green">Raider IO</h3>
                  <div class="ml-3">
                    <ul>
                      <li>
                        <a
                          href="https://raider.io/characters/eu/stormscale/M%C3%A9%C3%B2w#season=season-df-1"
                          target="_blank"
                          class="evoker-green"
                          >Meow
                        </a>
                      </li>
                      <li>
                        <a
                          href="https://raider.io/characters/us/area-52/Dragonfishi#season=season-df-1"
                          target="_blank"
                          class="evoker-green"
                          >Dragonfishi
                        </a>
                      </li>
                    </ul>
                  </div>
                </v-expansion-panel-text>
              </v-expansion-panel>
            </v-expansion-panels>
          </div>
        </v-expansion-panel-text>
      </v-expansion-panel>
    </v-expansion-panels>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }

  .evoker-green {
    color: #33937f;
  }
}
</style>
<script setup></script>

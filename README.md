#TREN TWIN CODE

use_bpm 122
use_synth :piano

live_loop :tren do
  play :c2
  sleep 0.5
  play :c2
  sleep 0.5
  play :r
  sleep 0.5
  play :G2
  sleep 0.5
  play :Gs2
  sleep 0.5
  play :D3
  sleep 0.5
  play :Gs2
  sleep 0.5
  play :G2
  sleep 0.5
end

sleep 14



live_loop :twin do
  play :c3
  play :g2
  play :c2
  sleep 0.5
  play :c3
  play :g2
  play :c2
  sleep 0.5
  play :r # r is a "rest" which makes no sound
  sleep 0.5
  play :g2
  sleep 0.5
  play :gs2
  sleep 0.5
  play :ds3
  sleep 0.5
  play :gs2
  sleep 0.5
  play :g2
  sleep 0.5
end

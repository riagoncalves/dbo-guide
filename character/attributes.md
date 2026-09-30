# Battle Attributes
---

Every weapon, every armor set and every monster has a **battle attribute** (also called property or prop). Attributes work like a rock-paper-scissors wheel: depending on the pairing you deal and take up to **10%** more or less damage.

| Icon | Attribute |
| - | - |
| ![](../_images/n.png) | None |
| ![](../_images/h.png) | Honest |
| ![](../_images/s.png) | Strange |
| ![](../_images/w.png) | Wild |
| ![](../_images/e.png) | Elegant |
| ![](../_images/f.png) | Funny |

## How It Works

- Your **weapon** attribute is compared with the target's **armor** attribute to modify the damage you deal.
- Your **armor** attribute is compared with the attacker's **weapon** attribute to modify the damage you take.
- Monsters have a single attribute that counts as both weapon and armor.
- The two icons next to your portrait show your current weapon and armor attributes. Hovering the attribute of a target shows how it affects you.

## Attribute Chart

Read the row as the attacker and the column as the defender.

<table>
  <tr>
    <th>Attacker ↓ / Defender →</th>
    <th><img src="../_images/n.png" /> None</th>
    <th><img src="../_images/h.png" /> Honest</th>
    <th><img src="../_images/s.png" /> Strange</th>
    <th><img src="../_images/w.png" /> Wild</th>
    <th><img src="../_images/e.png" /> Elegant</th>
    <th><img src="../_images/f.png" /> Funny</th>
  </tr>
  <tr>
    <td><img src="../_images/n.png" /> <b>None</b></td>
    <td>0</td><td>-5%</td><td>-5%</td><td>-5%</td><td>-5%</td><td>-5%</td>
  </tr>
  <tr>
    <td><img src="../_images/h.png" /> <b>Honest</b></td>
    <td>+5%</td><td>0</td><td>+5%</td><td><b>+10%</b></td><td><b>-10%</b></td><td>-5%</td>
  </tr>
  <tr>
    <td><img src="../_images/s.png" /> <b>Strange</b></td>
    <td>+5%</td><td>-5%</td><td>0</td><td>+5%</td><td><b>+10%</b></td><td><b>-10%</b></td>
  </tr>
  <tr>
    <td><img src="../_images/w.png" /> <b>Wild</b></td>
    <td>+5%</td><td><b>-10%</b></td><td>-5%</td><td>0</td><td>+5%</td><td><b>+10%</b></td>
  </tr>
  <tr>
    <td><img src="../_images/e.png" /> <b>Elegant</b></td>
    <td>+5%</td><td><b>+10%</b></td><td><b>-10%</b></td><td>-5%</td><td>0</td><td>+5%</td>
  </tr>
  <tr>
    <td><img src="../_images/f.png" /> <b>Funny</b></td>
    <td>+5%</td><td>+5%</td><td><b>+10%</b></td><td><b>-10%</b></td><td>-5%</td><td>0</td>
  </tr>
</table>

### Quick Reference

| Attribute | Strong against | Weak against |
| - | - | - |
| Honest | Wild (+10%), Strange (+5%) | Elegant (-10%), Funny (-5%) |
| Strange | Elegant (+10%), Wild (+5%) | Funny (-10%), Honest (-5%) |
| Wild | Funny (+10%), Elegant (+5%) | Honest (-10%), Strange (-5%) |
| Elegant | Honest (+10%), Funny (+5%) | Strange (-10%), Wild (-5%) |
| Funny | Strange (+10%), Honest (+5%) | Wild (-10%), Elegant (-5%) |

Any attribute has +5% against a target with no attribute, and gear with no attribute has -5% against everything else.

## Tips

- Check the boss attribute before a dungeon run. The [CCBD boss attributes](ccbd/boss-attributes.md) page lists every boss floor.
- Most monsters in the popular high-level hunting spots are **Wild**, **Elegant** or have no attribute, which makes **Strange** a common weapon choice for hunting and **Strange** or **Honest** common armor choices.
- Bosses such as Kraken and Cell-X have no attribute, so any attribute gives the same +5% there.
- In PvP the best attribute depends on what your opponents wear. Funny became popular because it beats both Strange and Honest.
- [Dogi attributes](character/dogi-attributes.md) and some titles raise the bonus of a specific attribute further.

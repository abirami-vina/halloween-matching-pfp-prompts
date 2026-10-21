# Building a Halloween Matching PFP Set

*Explore three Halloween matching PFP pairs made with Tsubaki.3 on PixAI and see how shared colors, props, and edits turned two avatars into a set.*

<img width="1378" height="777" alt="Anime header image of a red-haired witch winking and holding up a phone that shows matching profile pictures of a vampire and werewolf pair and a ghost and grim reaper pair, with a black-haired cat boy leaning over her shoulder in a candlelit attic." src="https://github.com/user-attachments/assets/c8343eff-c7a8-4e55-a5e4-c13349d9e3b4" />

*We created three Halloween matching PFP pairs in PixAI to see what makes two anime avatars look like a set while keeping each character distinct.*

Every October, profile pictures get a Halloween makeover. Friends turn into witches and ghosts, while couples look for a Halloween matching PFP (profile picture) that makes their avatars look like a pair. The trick is getting two images to look good together without making them look like the same character.

So, how do you make two Halloween PFPs match? Generally, it comes down to three things. You can define each character separately, give both images the same background, colors, lighting, and one recurring prop, and then check the two avatars side by side at profile-picture size, where small details can easily disappear.

We tested this out by creating three original Halloween anime PFP pairs with [Tsubaki.3](https://eap.pixai.art/go/abirami2), the newest anime model from [PixAI](https://eap.pixai.art/go/abirami). Each pair has its own theme.

Our first pair is a cozy duo of friends, a playful witch and the cat boy who follows her everywhere.

<img width="2048" height="1051" alt="Two anime Halloween profile pictures of a black-haired cat boy in an orange scarf and a red-haired witch in a purple hat, both in a candlelit attic with a full moon." src="https://github.com/user-attachments/assets/7cc4bbea-1897-4daf-95f4-1fc4362e7f99" />

*Kuro, a black cat familiar, and Hazel, his witch, as a Halloween matching PFP pair generated with Tsubaki.3.*

Next, we tried a couple with a different feel: an elegant vampire and a playful werewolf with a romantic red-rose theme.

<img width="2048" height="1051" alt="Two anime Halloween profile pictures of a silver-haired vampire and a gray-haired werewolf girl with a red rose, both on a gothic balcony under a full moon." src="https://github.com/user-attachments/assets/b0be48f4-3f52-4daf-9024-630dae3f4072" />

*Lucien, a vampire, and Rowan, a werewolf, generated with Tsubaki.3 on PixAI.*

For the last pair, we went with two friends who couldn’t be more different: a cheerful ghost and a grim reaper who would rather be asleep.

<img width="2048" height="1051" alt="Two anime Halloween profile pictures of a white-haired ghost girl and a sleepy grim reaper boy with a scythe, both in a misty pumpkin patch." src="https://github.com/user-attachments/assets/d2c6a3b5-711f-45b1-bd47-c25361bdb5fc" />

*Wisp, a ghost girl, and Mort, a grim reaper, generated with Tsubaki.3 on PixAI.*

All three pairs look like matching sets now, but they didn’t all get there the same way. The vampire and werewolf, and the ghost and reaper, matched on the first attempt because both prompts described the same scene from the start.

The witch and her cat familiar were trickier. We added their attic background later with an edit, and while each image looked great on its own, Kuro’s came out darker and lost most of the purple from Hazel’s, so the two looked like they came from different artists.

From that point on, Kuro kept changing in small ways, from his lighting and expression to his fang. If there’s one lesson from this test, it’s to write the shared scene into both prompts from the beginning. That lesson shaped how we approached the other two pairs, and it runs through every step below.

Let’s walk through each matching Halloween PFP pair, from planning the characters and writing their prompts to checking the results at profile-picture size and fixing the pair that needed a little more work.

## Three Halloween Matching PFP Ideas for Friends and Couples

Before we get into each pair, here’s the setup behind all of them. Every prompt had two parts: a description of the character, and a shared block about the background, colors, and lighting that we pasted into both prompts in a pair.

### The Settings We Used for All Six Avatars

To compare the results fairly, and so you can try the same approach yourself, we kept the settings identical for all six avatars. In PixAI, that meant Tsubaki.3 (v1) in Pro mode, with a 1:1 square shape and XL size (1408 × 1408), one image at a time.

Anything that could change the results on its own was left out, including [LoRAs](https://blog.pixai.art/en/what-is-lora-beginners-guide/) (small add-ons that teach a model a style or character), style presets, and the Quality Tag booster. The default Negative field stayed unchanged. The one extra setting was High Priority, which adds 1,000 credits per image for faster results.

<img width="2048" height="1039" alt="PixAI settings cropped to show Tsubaki.3 Pro, single image, 1:1 aspect ratio, XL resolution, and the Quality Tag toggle switched off, each outlined in orange. " src="https://github.com/user-attachments/assets/691ee356-cefd-4eb6-b131-785da38e1e64" />

*The Tsubaki.3 settings we used for all six avatars in PixAI.*

Prompt Helper was the last thing we switched off. It’s on by default and rewrites your prompt before sending it to the model, so turning it off means Tsubaki.3 received our wording exactly as typed.

The prompts we share here are the ones we actually used. All six images were generated in the third week of October 2026. This was a small, hands-on project rather than a full benchmark, so results may vary with different characters and prompts.

Next, let’s look at our first Halloween matching PFP pair, the witch and her black cat familiar.

## Pair 1: A Witch and Black Cat Matching Halloween PFP

Our first pair brings together Hazel, a playful witch who’s always winking, and Kuro, her black cat familiar. He has the look of someone who knows a secret but has no intention of sharing it. We wanted their profile pictures to match while still giving each character a look of their own.

<img width="1888" height="1056" alt="Anime witch with copper-orange hair reading a glowing spellbook in a candlelit attic, with a black-haired cat boy kneeling beside her and a full moon in a round window behind them." src="https://github.com/user-attachments/assets/9efcb7f9-993e-4c2d-b205-e60cd9274373" />

*Kuro and Hazel read a glowing spellbook in her attic, generated with Tsubaki.3 using both final profile pictures as references.*

To get that balance right, we planned which details Hazel and Kuro would share and which would set them apart. Here’s a closer look at the plan:

- Both images share a purple and pumpkin-orange palette, warm candlelight from the left, and a crescent moon, worn as Hazel’s silver earring and Kuro’s choker charm.
- Hazel has long, wavy copper-orange hair, emerald-green eyes, freckles, a playful wink, and a purple witch hat and cloak.
- Kuro has messy black hair with cat ears, golden cat-like eyes, a smug half-smile with one tiny fang, a black hoodie, and an orange knitted scarf.
- The two turn slightly toward each other, so their pictures feel connected side by side.

With those details in place, we wrote each character’s prompt separately. Hazel’s prompt focused on her hair, eyes, freckles, wink, and witch hat.

```text
Anime profile picture of a young witch girl, head-and-shoulders portrait, her face centered in the frame with a little space around her head. She has long wavy copper-orange hair, bright emerald-green eyes, light freckles across her nose, and a playful wink with a teasing smile, her head tilted slightly to the right. She wears a pointed dark purple witch hat with a pumpkin-orange ribbon band, its tip bending to one side, and a high-collared dark purple cloak. A small silver crescent-moon charm hangs from her left ear.
```

Kuro’s prompt followed the same structure, with details that made him look more like a cat and gave him a slightly mischievous expression.

```text
Anime profile picture of a young cat boy, head-and-shoulders portrait, his face centered in the frame with a little space around his head. He has short messy black hair with black cat ears, golden-yellow cat-like eyes with slit pupils, and a calm, smug half-smile showing one tiny fang, his face turned slightly toward the right side of the image. He wears an oversized black hoodie and a chunky knitted pumpkin-orange scarf. A small silver crescent-moon charm hangs from a thin black choker around his neck.
```

Both prompts ended with the same description of the background, colors, and lighting. We changed only “her” to “his” so the wording matched each character.

```text
Halloween night mood. Plain deep purple background with a soft orange glow and a few blurred floating candles. Warm candlelight from the left lights her face, with soft purple shadows on the right side. Anime illustration, crisp clean linework, soft two-tone cel shading, rich purple and pumpkin-orange color palette.
```

The first results were a good match. Hazel had all the features we asked for, and Tsubaki.3 added a few extra details, including a tiny jack-o’-lantern on her hat bow, a second crescent moon on the hat tip, and a small star above her earring. They suited her, so we kept them. Kuro also came out as planned, with his cat ears, golden eyes, and single fang, though his moon charm came out gold instead of the silver we asked for.

Sharing the same background helped bring the two pictures together. Both had the same deep purple backdrop, blurred candles, and orange glow, and the matching moon charms gave them another detail in common.

Their drawing styles were a little different, though. Hazel looked softer and slightly textured, while Kuro had darker, sharper lines.

We also felt the plain purple background could use more Halloween atmosphere, so we used an edit to move both characters into a candlelit witch’s attic with a full moon in the window. Hazel’s edit worked right away, but Kuro’s took several more attempts, which we’ll cover later in the troubleshooting section.

## Pair 2: A Vampire and Werewolf Halloween Couple PFP

For our second pair, we went with a Halloween couple made up of two classic monsters. Lucien is an elegant, composed vampire, while Rowan, a werewolf, has a much more playful side. We gave them one thing in common, a red rose, to tie their profile pictures together.

<img width="1280" height="720" alt="A silver-haired anime vampire offers a red rose to a smiling werewolf girl on a gothic balcony under a full moon, with rose petals drifting around them." src="https://github.com/user-attachments/assets/72a09e40-59ce-4eef-8bd4-7403eb2d4101" />

*Lucien offers Rowan a red rose on a moonlit balcony, generated with Tsubaki.3 using both final profile pictures as references.*

This time, we wanted the shared setting to do most of the work. Both characters would stand on the same gothic stone balcony, with a huge full moon behind their heads, castle silhouettes in the distance, and red rose petals drifting through the air.

We settled on deep crimson and moonlight blue, with cold blue light around their hair and shoulders and a warm red glow on their faces. The rose would appear in both images, pinned to Lucien’s collar and tucked behind Rowan’s ear.

Individual features kept the pair from looking too similar. Lucien has slicked-back silver-white hair, crimson eyes, pale skin, a calm smirk with small fangs, and a black high-collared Victorian coat with a red cravat. Rowan has a messy gray-brown wolf cut, fluffy wolf ears, icy blue eyes, a big grin, and a denim jacket with a fur collar.

Facing each other was part of the plan too. There was one change to our approach this time. With Hazel and Kuro, we added the shared setting afterward, which meant extra edits to get their images to match. For Lucien and Rowan, we included the entire scene in both prompts from the beginning.

Face size also mattered. So, each prompt asked for the face to fill about half the frame, helping the two characters look roughly the same size when their profile pictures were placed together.

Lucien’s prompt came first.

```text
Anime profile picture of a young vampire man, head-and-shoulders portrait, his face centered and filling about half of the frame. He has slicked-back silver-white hair, crimson red eyes, pale skin and a calm, elegant smirk showing two small fangs, his face turned slightly toward the right side of the image. He wears a black high-collared Victorian coat with a deep red cravat, and a single red rose is pinned to his collar.
```

Rowan’s prompt followed the same structure, with her wolf ears, icy blue eyes, and denim jacket setting her apart.

```text
Anime profile picture of a young werewolf girl, head-and-shoulders portrait, her face centered and filling about half of the frame. She has messy gray-brown wolf-cut hair with fluffy gray wolf ears, icy blue eyes and a big playful grin showing small sharp canines, her face turned slightly toward the left side of the image. She wears a worn dark-blue denim jacket with a shaggy fur collar over a black top, and a single red rose is tucked behind one wolf ear.
```

Each prompt ended with the same description of the balcony, moonlight, and rose petals.

```text
Halloween night on a gothic stone balcony, with a huge full moon directly behind the head, misty dark forest and castle silhouettes in the distance, and a few red rose petals drifting in the air. The background is softly blurred and darker than the character. Cold blue moonlight rims the hair and shoulders from behind, and a soft warm red glow lights the face from the left. Anime illustration, crisp clean linework, soft two-tone cel shading, deep crimson and moonlight-blue color palette.
```

Right from the first attempt, both profile pictures were good enough to use without any edits. The balcony, full moon, rose petals, and lighting lined up straight away.

Only a few details didn’t land exactly as planned. Rowan’s hair came out grayer than the gray-brown we asked for, while Lucien’s rose sat low on his coat rather than on his collar.

In the couple scene, Rowan also had a wolf tail that neither prompt mentioned. We liked how it looked, so we kept it. Compared with Hazel and Kuro, this pair took far fewer revisions.

## Pair 3: A Ghost and Grim Reaper Halloween Anime PFP

Last up are two friends who couldn’t be more different. Wisp is a cheerful ghost girl who can’t stay still, while Mort is a grim reaper who would rather be asleep. We wanted their profile pictures to match without losing that contrast.

<img width="1888" height="1056" alt="A cheerful white-haired anime ghost girl touches the cheek of a sleepy grim reaper boy, who leans against a glowing jack-o’-lantern in a misty pumpkin patch." src="https://github.com/user-attachments/assets/0bfc32af-fd3b-4bd4-8fdc-846c28d19228" />

*Wisp teases a sleepy Mort in a pumpkin patch, generated with Tsubaki.3 using both final profile pictures as references.*

Starting with the setting, we placed both characters in a misty pumpkin patch under a starry lavender sky. Glowing jack-o’-lanterns and floating will-o’-wisp lights filled the background, while a soft mint-green glow lit their faces. We kept the colors light and playful, using mint, lavender, and pumpkin orange.

Jack-o’-lanterns also gave us a way to tie the two characters together. Wisp wears a tiny glowing one as a hair clip, while Mort has a matching charm hanging from his hood string.

Beyond those shared details, we wanted the two to look quite different. Wisp has long, floating white hair with mint tips, big lavender eyes, a bright open-mouthed smile, and a tattered white ghost cloak. Mort has messy plum-black hair, sleepy silver-gray eyes with dark circles, a lazy half-smile, a black hooded robe, and a scythe over his shoulder.

Positioned on the left, Wisp turns toward the right, while Mort turns toward the left. That way, their pictures look toward each other when placed side by side.

Wisp’s prompt focused on her floating hair, lavender eyes, and ghost cloak.

```text
Anime profile picture of a cheerful ghost girl, head-and-shoulders portrait, her face centered and filling about half of the frame. She has long white hair with mint-green tips that floats weightlessly around her, big lavender eyes, softly glowing pale skin and a bright open-mouthed smile, her face turned slightly toward the right side of the image. She wears an oversized white hooded ghost cloak with a tattered hem, and a tiny glowing jack-o’-lantern hair clip sits above one ear.
```

Mort’s prompt followed the same structure, with his sleepy expression, dark robe, and scythe setting him apart.

```text
Anime profile picture of a sleepy young grim reaper boy, head-and-shoulders portrait, his face centered and filling about half of the frame. He has short messy dark plum-black hair, half-closed sleepy silver-gray eyes with faint dark circles and a small lazy smile, his face turned slightly toward the left side of the image. He wears a black hooded robe with the hood pushed down, the curved blade of a scythe rests over one shoulder, and a tiny glowing jack-o’-lantern charm hangs from his hood string.
```

Closing out both prompts was the same description of the pumpkin patch, lighting, and colors.

```text
Halloween night in a misty pumpkin patch under a starry lavender sky, with glowing jack-o’-lanterns and small floating will-o’-wisp lights in the distance. The background is softly blurred and darker than the character. A soft mint-green glow lights the face from the left, with lavender shadows on the right side. Anime illustration, crisp clean linework, soft two-tone cel shading, pastel mint, lavender and pumpkin-orange color palette.
```

Both profile pictures worked on the first attempt, and every trait on our list made it through. The shared background, lighting, and colors also lined up without any extra editing.

What surprised us was the style. Compared with the other two pairs, Wisp and Mort looked softer and more pastel, with a light, sketch-like finish. We had used almost the same art style wording as we did for Lucien and Rowan, yet the results looked quite different.

Pastel colors in the prompt may have pushed the images in that direction. Either way, the softer look suited these two and gave them their own take on the Halloween PFP anime style.

## How to Plan a Matching Halloween PFP Before You Generate

When you already have a fun pair of characters in mind, it’s tempting to jump straight into writing prompts. But when it comes to matching profile pictures, getting one character right is only half the job.

The second character needs to fit the first, and fixing a mismatch later can take several more attempts. We learned that firsthand with Kuro, whose background we only added after his first image was done.

We’d suggest starting every pair with a simple planning sheet. It’s what we used for all three of ours. It separates the details unique to each character from the ones both images need to share, which gives you a clear starting point for writing the prompts and helps the finished pictures look like a pair.

<img width="2048" height="1062" alt="Planning sheet with three columns, showing the cat boy Kuro and the witch Hazel with the features that stay different, and a middle column with both characters together and the shared colors, lighting, setting, and crescent moon prop.  " src="https://github.com/user-attachments/assets/4fe9c54a-423a-42ab-934e-7ff2f0bd3970" />

*The planning sheet for Kuro and Hazel, with their distinct features on the sides and the shared visual details in the middle.*

Here’s how we broke the plan down:

- **Character A and Character B:** List each character’s hair, eyes, outfit, and expression. Pick details that are easy to tell apart, like Hazel’s copper-orange hair and Kuro’s black hair.
- **A Shared Palette and Lighting Direction:** In our tests, this did more to connect each pair than anything else, especially at small sizes. For Hazel and Kuro, we used purple and pumpkin orange with warm candlelight from the left. If you need a starting point, PixAI has a handy breakdown of [Halloween color palettes](https://blog.pixai.art/en/halloween-drawing-ideas/) and lighting setups that pair well.
- **Complementary Expressions or Poses:** Give each character a different expression that still fits the pair, like Hazel’s wink and Kuro’s smug half-smile. Turning them toward each other helps the pictures feel connected.
- **One Recurring Visual Element:** Add one small prop to both characters. We used a crescent moon, as Hazel’s silver earring and Kuro’s choker charm, which Tsubaki.3 made gold. Our other pairs shared a red rose and a tiny jack-o’-lantern.
- **Framing for Two Separate Profile Pictures:** Each image still has to work on its own. We used head-and-shoulders portraits with the face centered and a little space around the head.

Using the same 1:1 square format for every avatar also helped. Since profile pictures are usually displayed as squares or circles, starting with square images meant we didn’t have to crop wider images and risk cutting off part of a face.

<img width="2048" height="787" alt="PixAI Image Dimensions panel with the 1:1 aspect ratio and XL 1408 × 1408 resolution highlighted, next to circle crops of two Halloween profile pictures. " src="https://github.com/user-attachments/assets/3bdad492-f3c6-4ed5-bf75-d5aa1c84679d" />

*The image dimensions settings we used for all six avatars, with a 1:1 aspect ratio and XL resolution.*

Once the sheet is filled in, the prompts almost write themselves. Everything on the sides becomes the character-specific part of each prompt, and everything in the middle becomes the shared block you paste into both.

To plan a pair for your own original characters (OCs), fill in the same details for each character. Then pick one setting, one light source, two or three colors, and a single shared prop. If a detail belongs to only one character, it goes on their side of the sheet. If both images need it, it goes in the middle.

## Generating and Refining a Halloween PFP Pair With Tsubaki.3

You might be wondering how the planning sheet turns into actual images. We created each avatar separately, one image at a time, using the two-part prompts from the sheet.

For Hazel and Kuro, there was one extra step: the edit that moved them into the witch’s attic.

You can edit an image directly in PixAI’s Generate box. Attach it, refer to it as @image1 in your prompt, and describe what should change and what should stay the same.

<img width="2048" height="560" alt="PixAI Generate box with an anime cat boy avatar attached as @image1, an edit prompt asking for softer lighting and purple tones, and a 5,300 credit cost." src="https://github.com/user-attachments/assets/e92cc225-c3ae-4f9a-841c-507e958297ef" />

*A Kuro edit in PixAI’s Generate box, with the avatar attached as @image1 and the credit cost displayed before generation.*

Starting with Hazel, we asked Tsubaki.3 to replace the plain background while leaving the character untouched. Here’s the prompt we used:

```text
Edit @image1. Replace only the plain purple background with a cozy witch’s attic at night: a large round window on the left side of the image showing a big glowing full moon, wooden shelves with potion jars and small carved jack-o’-lanterns on the right side, and a few lit candles. Keep the background softly blurred and darker than the character so her face stays the clearest part of the image. Keep the purple and pumpkin-orange color palette and the warm candlelight from the left. Keep the character exactly the same, including her face, wink, hair, freckles, eyes, witch hat, hat charms, earring, cloak, pose and framing.
```

Hazel’s edit worked on the first try. Kuro used the same prompt, mirrored for his side of the pair, but his result no longer matched hers. Fixing it took several more edits, at 5,300 to 6,200 credits each with High Priority on.

Next, we tried putting both characters in one image. We attached Hazel and Kuro’s final avatars as references and asked for a new scene, with Hazel reading a spellbook and Kuro kneeling beside her.

<img width="2048" height="922" alt="Two anime Halloween profile pictures of a witch and a cat boy, labeled @image1 and @image2, with an arrow pointing to a scene of both characters reading a glowing spellbook in an attic." src="https://github.com/user-attachments/assets/5d61c782-4222-4ee9-b1df-c95b9ee7c656" />

*Hazel and Kuro’s final avatars used as references for a single scene generated with Tsubaki.3.*

Both characters stayed recognizable, and the lighting and style matched closely since they were drawn together. Small details still changed. The silver moon on Hazel’s hat turned gold, and Kuro picked up a ring he never had. In the ghost and grim reaper scene, Wisp’s hair and eyes changed color on the first try, and naming those features in the prompt fixed it on the next one.

## Checking Your Halloween Matching PFPs at Profile-Picture Size

A pair can look great at full size but lose some of its appeal when it shrinks to a tiny circle next to a username. Before calling the avatars finished, we checked all six at the sizes people would actually see in profile pictures and chat lists.

We started by cropping each avatar into a square and a circle, the two shapes most apps use for profile pictures. Then we shrank them to chat-list size to see how the characters and their shared details held up next to a name and a message. We made all the crops ourselves after downloading the images, without changing the artwork.

<img width="2048" height="1562" alt="Six anime Halloween avatars in three pairs, a witch and cat boy, a vampire and werewolf, and a ghost and reaper, each shown as a square crop, a circle crop, and a small chat-list icon." src="https://github.com/user-attachments/assets/c1a09ea9-c806-4c39-949f-441072d7f373" />

*All six Halloween anime PFP avatars are shown as square crops, circle crops, and small chat-list icons, with each pair side by side.*

Let’s take a look at how each pair held up:

- **Witch and Cat Boy:** Both faces stayed inside the circle, and the purple and orange colors still matched. At chat size, Hazel’s orange hair stood out, but Kuro’s face takes up less of his frame, so he became mostly dark hair and a dark hoodie.
- **Vampire and Werewolf:** This pair held up best. The blue background and full moon made the two images feel connected, even at the smallest size. The circle crop did cut off most of Lucien’s rose, though, since it sat low on his coat.
- **Ghost and Grim Reaper:** The soft lavender background tied the pair together at every size, and both faces stayed clear. Mort’s jack-o’-lantern charm was partly cut off at the bottom, while Wisp’s hair clip stayed fully visible.

Across all three pairs, small props were the first details to disappear. The moon charms, Lucien’s rose, and Mort’s charm were either cropped out or too small to notice, while the backgrounds and lighting did most of the work of keeping each pair connected.

To keep an important prop visible, place it close to the face, as we did with Rowan’s rose and Wisp’s hair clip. It also helps to keep both faces at a similar size in the frame, so neither character loses too much detail when the images shrink.

## Why Your Halloween Matching PFPs Don’t Match

Fixing Kuro and Hazel taught us the most about what can go wrong when you try to make two profile pictures look like a set.

Things got tricky when we edited their backgrounds. Hazel’s witch’s attic came out soft and warm, with purple tones in the window and shadows. Kuro’s attic looked darker and sharper, and most of the purple had disappeared. Both images looked fine on their own, but side by side, they no longer felt like a matching pair.

<img width="2048" height="742" alt="Before-and-after comparison of a witch and cat boy Halloween PFP pair, with the cat boy’s image darker and less purple before the fix, and matching colors after." src="https://github.com/user-attachments/assets/0440f1ab-f3fa-4546-83c7-9c5fbe37f14b" />

*Kuro and Hazel’s matching Halloween PFP after the background edit, and the final pair after several fixes.*

Our first attempt was to attach Hazel’s image as a second reference and ask Tsubaki.3 to match its lighting and colors. Here’s the edit prompt we used:

```text
Edit @image1 so its lighting and colors match @image2. Make the image slightly brighter and softer, blur the background more so it looks out of focus like @image2, and add deep purple tones to the shadows, the wooden walls and the night sky in the window. Keep the round window and full moon on the right side, the shelves, the jack-o’-lanterns and the warm candlelight. Keep the character exactly the same, including his face, expression, hair, cat ears, eyes, hoodie, scarf, choker, moon charm, pose and framing.
```

This improved Kuro’s colors and gave his background the same soft blur as Hazel’s. But the second reference brought an unexpected problem. Tsubaki.3 picked up more than her lighting and colors. Kuro lost his fang, and his window moved to the left to match hers.

We then went back to the darker version and described the colors in words rather than using Hazel’s image as a reference. This time, Kuro kept his fang and window position, but his skin turned pale.

A follow-up edit warmed it up again, only to make it too orange. Each attempt fixed one issue while introducing another.

<img width="2048" height="1651" alt="Six versions of an anime cat boy avatar showing each edit attempt, including a lost fang, pale skin, overly orange skin, an angry expression, and the final fixed smile." src="https://github.com/user-attachments/assets/d7dec9f9-8a39-4499-aae4-bbf65e44685d" />

*All six attempts at fixing Kuro, from the first background edit to the final version.*

Eventually, we returned to the two-reference version because its colors matched Hazel’s best. We focused on restoring the missing fang without changing anything else. Our first edit prompt asked for a small adjustment.

```text
Add one tiny pointed fang showing at the corner of his mouth, turning his smile into a calm, smug half-smile. Keep everything else exactly the same, including his face, eyes, hair, cat ears, hoodie, scarf, choker, moon charm, the round window and moon on the left, the background, lighting, colors, pose and framing.
```

Instead of adding a tiny fang, Tsubaki.3 gave him two, opened his mouth, and changed his expression to an angry frown. We tried again, this time describing the mouth more precisely.

```text
A calm, smug closed-mouth half-smile with the lips closed, and one tiny pointed fang just poking out over the lower lip at one corner of the mouth.
```

That version worked on the first try using the Edit with Text option under the image.

Not every detail matched perfectly in the end. Kuro’s colors and expression now work with Hazel’s, but his moon still sits near the outer edge of his picture rather than facing hers, and his face is slightly smaller in the frame. Even so, the pair reads clearly as a set at profile-picture size, so we kept it.

Three things helped us get there. Changing one detail per edit made it easier to spot unwanted changes. Describing small features precisely, as we did with “lips closed,” left less room for Tsubaki.3 to interpret the instruction differently. And repeating key details, like the fang, in every edit prompt kept them from disappearing.

There’s another option for small fixes like these. PixAI also has a Repaint tool, which redraws only the area you brush over. We didn’t test it for this pair, but you can give it a try when you want to change one small feature, such as Kuro’s fang, without affecting the rest of the image.

<img width="1648" height="810" alt="PixAI Repaint screen showing an anime cat boy avatar on a canvas, brush and mask tools at the top, and Masked Area settings for feathering, strength, and repaint mode on the right." src="https://github.com/user-attachments/assets/01237a55-7faa-4186-a9fd-e6b4edd88b1e" />

*PixAI’s Repaint screen lets you brush over just the area you want to change.*

## Halloween Matching PFP FAQs

By the end of the project, all six characters felt like part of the same Halloween crew, so we brought them together for one last group selfie. It was also a fun test of how well Tsubaki.3 could keep three pairs recognizable in a single image.

<img width="1678" height="937" alt="Anime Halloween group selfie of six characters in a candlelit room under a full moon, with a red-haired witch holding an orange phone, a black-haired cat boy, a silver-haired vampire, a gray-haired werewolf girl with a red rose, a white-haired ghost girl, and a sleepy grim reaper." src="https://github.com/user-attachments/assets/13e3b00c-01aa-482a-8587-1bd3f57d8bae" />

*All six characters together in one Halloween group selfie.*

Making these pairs raised a few questions along the way. Whether you’re starting from scratch or bringing two existing OCs together, here’s what we found:

- **Can I make matching Halloween PFPs with two existing OCs?** Yes. Our characters were new, but the same planning works for existing OCs. Describe them the same way in every prompt and build the shared scene around them. For costume ideas, try PixAI’s [witch, vampire, and ghost prompt ideas](https://blog.pixai.art/en/halloween-ghost-witch-vampire-prompts/).
- **Do both avatars need the same prompt?** No. We wrote a separate description for each character and added the same scene block to both, which kept the characters distinct while matching the look.
- **How can I keep two characters distinct?** Give them easy-to-spot differences in hair, expression, and outfit, like Lucien’s slicked-back silver hair and Rowan’s messy wolf cut. A shared prop worn differently, like Lucien’s and Rowan’s red roses, connects them without making them look alike.
- **Should I generate a pair together or as separate images?** Separately, for profile pictures. Each avatar keeps its full size and framing, and you can fix one without changing the other. Images with both characters work better as bonus images, like a banner.

## What Makes a Halloween Matching PFP Pair Work?

In our tests, the pairs that matched best had the full scene written into both prompts from the start. Describing each character separately, then giving both prompts the same background, colors, and lighting, got two of our three pairs right on the first try.

Tsubaki.3 handled most of the work well. It kept each character’s key features, followed the shared scene, and even brought both characters together in a single image.

Kuro and Hazel were the exception, since we added their background only after generating the avatars, and it took several more edits to get them looking like a pair again.

Before sharing your own Halloween matching PFPs, put both avatars side by side and shrink them to profile-picture size. Check that both faces are easy to see, the colors still work together, and any important props sit close enough to the face to survive the crop.

Ready to create a matching Halloween PFP with a friend or partner? Try [Tsubaki.3](https://eap.pixai.art/go/abirami2) on [PixAI](https://eap.pixai.art/go/abirami) and give your characters a world they can share.

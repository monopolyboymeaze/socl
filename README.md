# Simplified Open Community License

This repository contains the **Simplified** Open Community License (SOCL V1). SOCL is a license designed to satisfy all of the goals of the original [Open Community License][col] while being more succinct and legally sound.

Like it's predecessor, SOCL:

> [Is] a license designed to allow open access to community including the essential right, the right-to-repair, while promoting fair competition. [sic]

Unlike its predecessor, SOCL:

- Features **345** less words (long form) or **infinitely** less words (short form).
- Is backed by literal centuries of case law.

You might be wondering how SOCL accomplishes this with such brevity, luckily for you we have a [Comparison](#comparison) and [FAQ](#faq) just for you, brave scholar!

[ocl]: https://github.com/OpenCommunityLicence/OpenCommunityLicence

## License

The license comes in two forms, the **long form** and **short form**. You can use either form when releasing your project under SOCL.

### Long Form

Use the following template for the long form:

```
© {Initial year of publication} {Copyright holder},  All Rights Reserved
```

For example:

```
© 2025 Scrooge Industries, All Rights Reserved
```

If you're unable to utilize unicode characters, you can use the **extra long form**:

```
Copyright {Initial year of publication} {Copyright holder},  All Rights Reserved
```

For example:

```
Copyright 2025 Beavis, Inc., All Rights Reserved
```

That's it!

### Short form

For those that really value brevity and simplicity, SOCL's short form offers an unbeatable solution. Simply use:

```
```

That's not a mistake, it's literally nothing. That's because in most countries [copyright is automatic][automatic-copyright] and the rights are reserved for the copyright holder, satisfying the long form without so much as as wasting a single character!

[automatic-copyright]: https://www.copyright.gov/help/faq/faq-general.html


## Comparison

SOCL's intense conciseness might have startled you. We don't wish to alarm, so we've made this comparison between SOCL and its [overly verbose inspiration][ocl-text]. Let's break it done section by section.

> OCL pertains to intellectual property applied in licensor‘s products
and/or its components (hardware and software) which is distributed
under such, including copyright, design, and patent. [sic]

This is unnecessary since it's just poorly describing what a license.

> All licensors‘s copyrights, designs, and patents as far as relevant to products and/or its components under OCL are **community open** ... [sic] [emphasis added]

The term **community open** is undefined and meaningless. OCL is essentially saying that you can download a copy of the source designs for some aspects of the project. There's no need for a license to specify this, as the copyright holder is free to distribute any supplemental material such as technical drawings and source code without granting any rights for reproduction. This is no different from an appliance manufacturer making schematics and such available to their customer. Just because you have access to something doesn't mean you have any rights to reproduce it. For example, you can legally view just about any patent but it would be illegal to reproduce the subject.

In summary, this clause doesn't grant any rights or add restrictions or obligations, so it can be removed.

> as the aim of OCL is to allow open access to community including the essential right, the right-to-repair, by giving users complete freedom of use, copy, modification, and hack, while promoting a fair competition by securing intellectual property rights to prevent vendor locking and patent trolling. [sic]

Good lord is this a word burger. We're going to break out the bulleted list- don't worry, they're not *real* bullets:

- `essential right [sic]`: We have no idea what this means. 🤷‍♀️
- `the right-to-repair [sic]`: According to our [semi-reliable source][repair.org], "Right to Repair" comes into play when products include deceptive end-user license agreements or contracts. These contracts would supercede a license like OCL (and SOCL, and MOCL). Repair.org also claims that "The U.S. Copyright Office (USCO) clarified in 2016 that copyright law does not prohibit repair, customization, security research, or resale.", so from our understanding unless you've got a supervillian lawyer coming up with EULAs that prevent users from sneezing in the vicinity of your product, you don't need to explicitly spell this out as users already have these rights. Even if this weren't the case, there's nothing in OCL that defines what this right is supposed to be, so it's effectively meaningless.
- `giving users complete freedom of use, copy, modification, and hack [sic]`: This is contradicted by the limitations spelled out in later parts of the OCL. Users do not have **complete** freedom, as they are not allowed to use an OCL-licensed project for commercial purposes. As noted in the previous point, copyright does not prohibit repair or customization. Given that this is no different from "all rights reserved", it's unnecessary.
- `while promoting a fair competition by securing intellectual property rights to prevent vendor locking and patent trolling. [sic]`: This introduces new terms without ever defining them, and does not provide any clarification on other parts of the license. As far as we can tell this is posturing and meaningless.

In summary, this clause doesn't grant any rights or add restrictions or obligations, so it can be removed.

> NOTE that any part of the product and/or its component provided under a
license incompatible with OCL remains unaffected by OCL. [sic]

This is true but unnecessary. This is the case with any work that is derived from third party sources. It is worth nothing that other, real, licenses typically enumerate obligations such as including a notice or acknowledgement of the incorporated work.

In summary, this clause doesn't grant any rights or add restrictions or obligations, so it can be removed.

> As an non-commercial END USER

OCL does not ever define `non-commercial END USER [sic]` but we can surmise that they mean anyone using the damn thing, so this applies to everyone.

> YOU MAY use, copy, modify, hack the product and/or its components as
you wish! [sic]

As mentioned previously, copyright alone does not prohibit repair, customization, security research, or resale. So other than "copy", everything listed here is redundant. "copy ... as you wish [sic]" is contradicted by the restriction on being able to sale copies, so this is effectively no different from "all rights reserved" and can be removed.

> YOU SHOULD support the 3D printing community by sharing your creations and modifications.

Yeah, and dentists say we should floss more often. This is a contract, not a suggestion box. This is weirdly specific to 3d printer and doesn't add anything meaningful, so it can be removed.

> If you distribute your creations, modifications, or any such derivatives YOU MUST do so under OCL or any non-commercial, share-alike license allowing other community members to do everything that YOU MAY. [sic]

There is unfortunately no known non-commercial, share-alike license that is clearly compatible with OCL, so we do not recommend attempting to re-license your derivatives. As such, this clause is useless and can be omitted.

> This does not concern your creations and modifications that are not derived from the product and/or its components. [sic]

No shit! That's how copyright works, my good man. You took the time to write out a fundamental aspect of copyright so it can safely be omitted.

> As a commercial BUSINESS USER [sic]

Again, OCL does not ever define `commercial BUSINESS USER [sic]`, but based on the functionally inconsequential distinction and practically identical rights and restrictions applied to the two groups, we can skip this.

> YOU MAY use the product and modify it to your use case solely for your internal production use. [sic]

Once again, already covered within the existing copyright framework. Unless you're adding additional contracts or EULAs (I see you, John Deere), this isn't necessary, and if you are, then this is superceded by those contracts.

> YOU MUST NOT modify the product and/or its components for any commercial purpose other than your internal production use. [sic]

We came up with two interpretations for this. The charitable one is that this means you can't create copies, in part or whole, of an OCL-licensed product and sell them. That interpretation is fundamentally the same as "all rights reserved", so another win for our hungry backspace key. The uncharitable one is that you couldn't even modify an OCL-licensed machine in a way that makes you money that wasn't anticipated by the original manufacturer. This would be oddly similar to the dastardly evil anti-Right to Repair EULAs we mentioned earlier, so we're gonna hope and assume the OCL authors did not mean this.

> YOU MUST NOT copy or in any way replicate the product and/or its components for any commercial purpose excluding your internal right-to-repair without obtaining a separate business license or repair license. [sic]

Once again we've found ourselves reading a poor description of rights and activities that copyright alone does not prohibit. Once again this is functionally identical to "all rights reserved" and can, once again, be removed. Who needs compression when you can just delete stuff?

> Licensor‘s products and/or its components under OCL MUST NOT BE subject to any systematic or automated text and/or data mining or other text and/or data collection activity in relation to the product without explicit permission. [sic]

Finally, something halfway novel. Unfortunately, this is already supposed to be protected under copyright but good luck enforcing that against AI companies. This doesn't really add anything, so it can be removed.

> To promote ease of understanding of OCL Licensor keeps and updates a database of products and/or its components licensed under OCL and good practice at [link to the database]. [sic]

We noticed that the `[link to database]` doesn't go anywhere, and since no one likes a dead link, we decided to do Zelda a favor and just remove this sentence.

> For practical examples of how this license applies, see the examples/ directory. [sic]

We peered into OCL's `examples/` directory and noticed that it comprised only of Prusa Research™️ by Josef Prusa™️ examples, which we found to be in poor taste. We considered including examples for SOCL, but then we realized you can probably find an example within arm's reach, maybe even the device you're reading this on, how quaint!

In summary, we were able to remove every clause from OCL while maintaining the rights and restrictions it so laboriously laid out. Our efficiency is truly marvelous.

[ocl-text]: https://github.com/OpenCommunityLicence/OpenCommunityLicence/blob/cce4f263fa79eed19028dac03697116a6dfc6f39/LICENSE
[repair.org]: https://www.repair.org/stand-up

## FAQ

### Are OCL/SOCL open source licenses?

Hell yeah, brother! You can download the **source** and you can **open** it! Provided you have the right software installed, and no, we will not help you with that, so please stop asking!

Some so-called "open source" "purists" would rattle on about [freedoms and definitions][osd] but we know you ain't got time for that shit. We know you're trying to sell your product and you don't want to be embarrased in front of your cool open source friends. Rest easy, friend, OCL/SOCL are as open source as they come!

[osd]: https://opensource.org/osd

### Should I consult a lawyer before using OCL/SOCL?

Oh, absolutely. They'll at least get a good laugh, and you'll feel better about paying a lot of money to talk to a dude for 5 minutes if he has a funny sounding laugh. You should also talk to a friend, a parent, or a guardian, and possibly a pet. If you're religious, consider asking your priest/rabbi/coven mother what they think.

### Why make SOCL so simple?

To quote our [muse and inspiration][lol]

> It is easier to prepare a long license than a short one. With OCL we aimed for the latter for it to be understandable without a law degree and make intention of the licensor as clear as possible. [sic]

We decided to be maximalist in our minimalism. Perfection is only achieved when there's nothing left to remove, after all!

[lol]: https://github.com/OpenCommunityLicence/OpenCommunityLicence/issues/6#issuecomment-3682169793


### Copyright doesn't protect functional hardware, only artistic works, how does OCL/SOCL address this?

That's the neat thing, it doesn't! If someone infringes on a copyrightable aspect of your OCL/SOCL-licensed project, you can attempt legal action for that. If you have patents or trademarks that are being violated, you can attempt legal action for that. No copyright license can provide protection if you are not willing and capable of persuing legal action against violations.

We would like to note that the OCL authors claim that grandpa [OCL is supposed to be an "IP License"][patent-claim] that combines copyright, design patents, and utility patents, but OCL notably does not grant any additional patent rights nor does it include patent-specific features like clawback or retaliation clauses that more sophisticated licenses have (like Apache Software License).

[patent-claim]: https://github.com/OpenCommunityLicence/OpenCommunityLicence/issues/1#issuecomment-3675178129es/1

### Will OCL/SOCL stop China?

We're so glad you stopped by, Josef! We still vividly remember your driving motivation behind abandoning open source and creating OCL:

>
> Chinese will steal all the open-source development to the last bit
>
> -[@josefprusa](https://x.com/josefprusa/status/1686017606094868482)

The truth is, neither OCL or SOCL are powerful enough to stop China. No license is, unfortunately. They are children that are ill-prepared for economic, political, and racist warfare.

We are sympathetic to the obstacles faced by your business. At least one of us has a background in the music instrument industry, which is lousy with cheap clones of lousy guitars (and other instruments, if you can believe it). We're fans of your products and are thankful for the work you've shared back to the community. However, according to our experts, open source is an IP strategy and not a subsitute for a business strategy. We think you should consider doing some introspection on why years of blaming open source and China have not managed to increase your market share.

P.S.: If you're still here, Josef, we wanted to let you know that we'd pay for the first session of laser tattoo removal if you wanna get that pesky OSHW tattoo taken care of. Let us know.

### What alternatives are there to OCL/SOCL?

If you want to do *real* open source, not that imitation stuff, you can use a real, big girl license:

- [CERN's OHL][cern-ohl] is the gold standard for hardware-specific licenses, and includes strongly reciprocal, weakly reciprocal, and permissive variants.
- [Creative Commons][cc] has a bestiary of useful, well-defined licenses for a variety of purposes.

[cern-ohl]: https://gitlab.com/ohwr/project/cernohl/-/wikis/home
[cc]: https://creativecommons.org/

If you don't like open source, what the hell are you doing here? Just do the normal shit! Get out!

## Copyright

SOCL itself is published under the following terms:

```
Simplified Open Community License (SOCL)

© 2025 Imogen Theep

You are free to use, copy, redistribute, modify, inject, memorialize, worship, fold, bury, shred, bend, spindle, mutilate, or otherwise do whatever you'd like with this document so long as:

1. You acknowledge its satirical nature.
2. You are not Josef Prusa. If you are Josef Prusa, you are already in violation of the terms of this license. Sorry, buddy.
3. You have not read past the 2nd term of this license.

If you have read to this point, or if you have had an AI summarize to this point, you have violated this license and must sincerely apologize in order to regain your rights. If you subsequently re-read past the 2nd term, you will have to apologize again. And again.
```

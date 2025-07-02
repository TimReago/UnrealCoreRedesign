# UnrealCoreRedesign
PURPOSE: Redesigning the Unreal Engine core systems to eliminate UHT and other non-standard C++ feature - with focus on stabilizing the build environement for small dev teams.

Unreal Engine is known for development instabilities.  Whereas, traditional C++ is a much more stable and proven development base.

Google AI: "Many [Unreal Engine] developers encounter challenges getting a stable and predictable setup, and it can feel like a constant battle against crashes, compiler errors, and other issues that disrupt workflow.".

Google AI: "One source estimated the UE 4.23.1 codebase at around 16 million lines of code, based on file size."

Because of the instability of the UE tools, with almost 2 years of attempts to get to a stable build environment. It seems more like the stability of the UE game development environment for a solo deve is more of an oscillating nightmare.  Not what I had initially hoped to see when I first chose to proceed with Epic's Unreal Engine.

Google AI: "Realistically, it would be incredibly difficult, if not impossible, for one person to reconstruct the entire Unreal Engine 5.6 codebase from scratch ... [up] to the point where modules could [then start being] added."

Because I had already jumped in to rebuild the engine from startup, and was having considerable success: stable, steady, predictable. My questions to Google AI were more like: If I rebuild the engine startup up to around the tick functions, which now appears to be achievable for one person, would there be a point where I could start to incorporate larger chunks of existing code without significant changes, and as a means to arrive at a more stable game development base?

Google AI: "While UE5's C++ code structure is based on standard conventions, its use of custom build tools, reflection, and engine-specific features makes it a highly specialized codebase. Reforming it to be purely standard C++ would be a massive undertaking that would require recreating many of the core features that make UE5 such a powerful engine."

Google AI: "Creating a 'closed-source project' on GitHub to manage your modified Unreal Engine core is generally acceptable under Epic's Unreal Engine End User License Agreement (EULA), but with specific restrictions and considerations. ... Controlled Access: A private GitHub repository allows you to control who can access and contribute to your code base. You can grant access only to your collaborators who are also licensed to use the same version of Unreal Engine."

Google AI: "A private GitHub repository is a suitable approach for managing your custom Unreal Engine core, but it's crucial to adhere to the EULA's restrictions on public distribution of the Engine Code. You can share your modified engine [source code only] with other licensed developers."

Google AI: "In summary, maintaining a private development process for your custom Unreal Engine core is the recommended approach to ensure stability and efficiency as a solo developer. Once you have a stable foundation, you can explore options for controlled collaboration with other developers who have access to the same version of the Unreal Engine."

And so, I forwarded the request to Epic Licensing, asking if it would be alright to start this private github repository for these development purposes.  Epic, thus far, has not objected.  And so here we are.

Let's dig in, we can do this.

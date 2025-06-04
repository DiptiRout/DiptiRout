## Hi there, I'm Diptiranjan 👋
I'm a passionate Apple Application Developer specializing in Swift and SwiftUI, crafting high-performance Apple applications. Recently, I've begun exploring Flutter to broaden my horizons in cross-platform development.

**Clean Architecture + MVVM**
```mermaid
flowchart TD
    %% ===== Main Layers =====
    App[App Target] --> AppCoordinator
    App --> Feature
    App --> AppUI
    
    AppCoordinator --> Feature
    
    Feature --> Domain
    Feature --> AppUI
    
    Data --> Domain
    Data --> Infra
    
    %% ===== Style Enforcement =====
    style Domain stroke:#00aa00,stroke-width:3px
    style Infra stroke:#ff5555,stroke-width:3px
    style AppUI stroke:#5555ff,stroke-width:3px
    
    %% ===== Legend =====
    legend[("
        🟢 Domain: Independent (Pure Swift) | 
        🔴 Infra: Independent (Raw Services) | 
        🔵 AppUI: Independent (Atomic Design)
    ")]
```

## What I Do
### Apple Developer:
- I build robust iOS applications using Swift & SwiftUI, and I'm always on the lookout for cutting-edge demos involving AR, VR, AI, ML.
### Flutter Beginner:
- I'm diving into Flutter to learn how cross-platform development can complement my iOS expertise.
### Gamer & Manga Enthusiast:
- When I'm not coding, you'll find me playing MOBA Games and reading Manga & Manhwa.

## What I'm Looking For
- Inspiring projects and demos that leverage Swift/SwiftUI and modern Apple frameworks.
- Innovative examples of AR, VR, AI, and ML in iOS development.
- Community tips and tutorials for Flutter as I embark on this new journey.

### Connect with me:
[<img align="left" alt="codeSTACKr | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]

<br />

---

[linkedin]: https://www.linkedin.com/in/diptiranjan-rout-ios-dev

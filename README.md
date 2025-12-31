# Bench Press Game

A skill-based browser game where you progress through increasingly difficult weightlifting challenges.

## Objective

Work your way up to bench pressing 500 lbs by completing levels and earning experience points (XP).

## How to Play

### Basic Controls

- **Lift**: Tap and hold the "Lift" button to raise the barbell
- **Lower**: Release the button to let the barbell drop back down
- **Target Sections**: Click on highlighted "Gains" sections to complete reps

### Game Mechanics

#### Reps System
- Each level requires you to complete a set number of reps (starting with 5)
- To earn a rep, move the barbell between highlighted **Gains** sections without touching the **Rest** zone
- The highlighted section alternates - click it to earn the rep and move to the next target
- If the barbell enters the **Rest** zone, your rep counter resets to 0
- Complete all required reps to advance to the next level

#### Zones

**Gains Sections**
- Your target zones for completing reps
- One section will be highlighted with a → arrow and gold text
- Click the highlighted section to score a rep and switch targets

**Fatigue Zone**
- Passing through this zone applies a **Fatigue** status effect
- Each stack reduces your maximum lifting height by 10%
- Can stack up to 10 times (100% reduction = unable to lift)
- Lasts 30 seconds per stack (max 120 seconds total)

**Rest Zone** (Bottom)
- If the barbell enters this zone mid-rep, your rep counter resets
- Use this zone strategically when you've maxed out your reps

#### Progression

- **Starting Weight**: 50 lbs
- **Goal Weight**: 500 lbs
- Complete all reps in a level to unlock the next level with increased weight
- Earn XP for each completed rep

### Strategy Tips

1. **Avoid Fatigue Early**: Try to skip the Fatigue zone on your first few reps when you need maximum height
2. **Plan Your Path**: Watch the highlighted sections - sometimes you'll need to go high, sometimes low
3. **Don't Rest Prematurely**: Touching the Rest zone before completing your reps will reset your progress
4. **Manage Fatigue**: If you have too many Fatigue stacks, wait for them to expire before attempting difficult lifts

### Status Effects

#### Fatigue
- **Effect**: Reduces max lifting height by 10% per stack
- **Duration**: 30s per stack
- **Max Duration**: 120s
- **Max Stacks**: 10
- **How to Get**: Pass through Fatigue zones
- **How to Remove**: Wait for the timer to expire

### Auto-Drop Mechanic

If you hold the barbell at maximum height for 1 second, it will automatically drop. Use this to your advantage when timing difficult landings.

## Debug Mode

Press the Konami Code variant (↑ ↓ ↑ ↓ ← →) to open the debug menu with developer tools.

## Winning the Game

Progress through all levels to reach the 500 lb bench press goal. Each level increases in difficulty with higher weight and more complex zone layouts.

Good luck, and may your gains be legendary! 💪

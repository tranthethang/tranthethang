```python
from dataclasses import dataclass, field
from typing import ClassVar

@dataclass
class DeveloperProfile:
    name: str
    location: str
    since: int
    skills: list[str]
    goals: list[str]
    
    _intro_template: ClassVar[str] = """
Hi, I'm {name} from {location}.
Developer since {since} — still running on caffeine and curiosity.
Roles: {skills}.
I focus on strong foundations over chasing version numbers.

Upcoming goals:
{goals}"""
    
    def __str__(self) -> str:
        return self._intro_template.format(
            name=self.name,
            location=self.location,
            since=self.since,
            skills=', '.join(self.skills),
            goals='\n'.join(f"  - {goal}" for goal in self.goals)
        ).strip()


if __name__ == "__main__":
    profile = DeveloperProfile(
        name="Alex Tran",
        location="Hanoi, Vietnam",
        since=2011,
        skills=["Backend", "Frontend", "System Architecture", "Team Leadership"],
        goals=[
            "Master DevOps practices and cloud infrastructure",
            "Build and deploy ML models in production",
            "Fine-tune pre-trained models for domain-specific tasks"
        ]
    )
    
    print(profile)
```
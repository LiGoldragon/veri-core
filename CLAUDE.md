# sema-core

Primordial ontological foundation. The four prime generators and their
derived composites — the irreducible building blocks of the sema format.

## What Sema Is

Sema is the universal typed binary format. Not a library, not a framework —
the format. Everything serializes into sema. rkyv is the serialization.
The domain ordinals are the bytes. The inter-linking is content-addressed.
Zero-copy, mmap-ready, deterministic.

Sema is the bet that meaning has structure, structure has primes, and
primes have bytes.

## The Four Prime Generators

Every domain in the system decomposes into cardinalities drawn from the
first four primes. These are not arbitrary — they converge across music
(prime harmonic limits), Vedic philosophy (dvandva/guna/bhuta/graha),
astrology (polarity/modality/dignity/planet), group theory (free generators
of the positive rationals), and type theory (irreducible enum cardinalities).

- **Polarity (2)** — the irreducible binary. Sect, gender, purusha/prakriti.
- **Modality (3)** — how action unfolds. Cardinal/fixed/mutable. Sattva/rajas/tamas.
- **Dignity (5)** — quality of fitness. Domicile/exaltation/triplicity/term/face.
- **Archetype (7)** — irreducible forces. The seven wandering stars.

Prime-cardinality enums cannot be decomposed into smaller enums — they are
the atoms of the type algebra. All composite cardinalities factor into these:
4 = 2x2, 12 = 2x2x3, 36 = 2x2x3x3, 360 = 2x2x2x3x3x5.

## The Thesis

Natural language is enumerable. The prime generators produce every possible
meaning through fractal composition. A sentence is a tree of domain
references — each node a deterministic ordinal within its domain. The tree
IS the meaning. Text is a lossy projection.

Structs and enums ARE the natural language specification. Per-language
translation tables (English, Chinese, sign language, color, sound) map
domain paths to surface forms. The domain tree is language-independent.

This extends to all media. Audio is typed signal composition. Video is typed
visual composition. Not opaque blobs with container formats — typed all the
way down, editable at the semantic level, zero-copy, structurally shareable.

## Role in the Stack

sema-core provides the generators and derived composites. sema (the
application layer) builds programming-logic domains on top. Everything else
in the ecosystem exists to serve sema:

- aski is how you write sema definitions
- nexus is how you talk to a sema world
- arbor is how sema versions itself
- criome-store is where sema bytes live on disk
- criome is the runtime that hosts sema worlds
- samskara is a sema world

## String Fields Are Transitional

Every string field in every schema is a placeholder for a sema domain
composition that hasn't been specified yet. As the ontology grows, each
string field collapses from a 32-byte content-addressed hash to a typed
domain tree of ordinals. Sema objects get smaller and faster as more of
the world is enumerated.

## VCS

Jujutsu (`jj`) is mandatory. Always pass `-m`.

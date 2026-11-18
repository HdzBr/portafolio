import { createFileRoute, Link } from "@tanstack/react-router";
import { ArrowRight, ArrowUpRight } from "lucide-react";
import { Button } from "@/components/ui/button";
import { BrowserFrame } from "@/components/site/browser-frame";
import { LivePreview } from "@/components/site/live-preview";
import { ProjectCard } from "@/components/site/project-card";
import { WHATSAPP_URL } from "@/data/contact";
import { displayUrl, projects } from "@/data/projects";

export const Route = createFileRoute("/")({
  head: () => ({
    meta: [
      { title: "hzbdigital — Diseño y desarrollo web" },
      {
        name: "description",
        content: "hzbdigital diseña y construye sitios web modernos. Explora nuestros proyectos en vivo.",
      },
      { property: "og:title", content: "hzbdigital — Diseño y desarrollo web" },
      {
        property: "og:description",
        content: "hzbdigital diseña y construye sitios web modernos. Explora nuestros proyectos en vivo.",
      },
      { property: "og:type", content: "website" },
      { name: "twitter:card", content: "summary_large_image" },
    ],
  }),
  component: Index,
});

const services = [
  { title: "Diseño web", text: "Interfaces modernas, claras y pensadas para convertir visitas en clientes." },
  { title: "Desarrollo", text: "Sitios rápidos, adaptables a cualquier pantalla y fáciles de mantener." },
  { title: "E-commerce", text: "Tiendas en línea con catálogo visual y una compra sin fricción." },
  { title: "Identidad digital", text: "Una presencia coherente que hace que tu marca se vea profesional." },
];

function Index() {
  const featured = projects[0]!;
  const marquee = [...projects.map((p) => p.name), "Diseño web", "Desarrollo", "E-commerce"];

  return (
    <>
      {/* Hero */}
      <section className="relative overflow-hidden">
        <div className="bg-grid pointer-events-none absolute inset-0" />
        <div className="bg-fade pointer-events-none absolute inset-0" />
        <div className="container-page relative pb-20 pt-20 md:pt-28">
          <div className="animate-fade-up mx-auto max-w-4xl text-center">
            <span className="inline-flex items-center gap-2 rounded-full border border-border px-4 py-1.5 font-mono text-xs text-muted-foreground">
              <span className="size-1.5 rounded-full bg-foreground" /> Estudio digital · Portafolio
            </span>
            <h1 className="text-shine mt-8 font-display text-5xl font-bold leading-[1.02] tracking-tighter md:text-7xl lg:text-8xl">
              Webs que hacen ver tu marca en otro nivel.
            </h1>
            <p className="mx-auto mt-6 max-w-xl text-lg text-muted-foreground">
              En hzbdigital diseñamos y desarrollamos sitios modernos y profesionales. Mira nuestros
              proyectos funcionando en vivo.
            </p>
            <div className="mt-10 flex flex-wrap justify-center gap-3">
              <Button asChild variant="hero" size="xl">
                <Link to="/proyectos">
                  Ver proyectos <ArrowRight />
                </Link>
              </Button>
              <Button asChild variant="line" size="xl">
                <a href={WHATSAPP_URL} target="_blank" rel="noreferrer">
                  Hablemos
                </a>
              </Button>
            </div>
          </div>

          <Link
            to="/proyectos/$slug"
            params={{ slug: featured.slug }}
            className="animate-fade-up group mx-auto mt-16 block max-w-5xl [animation-delay:200ms]"
          >
            <div className="animate-float">
              <BrowserFrame
                url={displayUrl(featured.url)}
                actions={<ArrowUpRight className="size-4 text-muted-foreground transition-colors group-hover:text-foreground" />}
              >
                <LivePreview url={featured.url} title={featured.name} />
              </BrowserFrame>
            </div>
          </Link>
        </div>
      </section>

      {/* Marquee */}
      <section className="overflow-hidden border-y border-border py-6">
        <div className="animate-marquee flex w-max gap-12">
          {[...marquee, ...marquee].map((item, i) => (
            <span
              key={i}
              className="flex items-center gap-12 font-display text-2xl font-semibold tracking-tight text-muted-foreground md:text-3xl"
            >
              {item} <span className="text-foreground/30">✦</span>
            </span>
          ))}
        </div>
      </section>

      {/* Projects */}
      <section className="container-page py-24 md:py-32">
        <div className="flex flex-col gap-6 md:flex-row md:items-end md:justify-between">
          <div>
            <p className="font-mono text-xs uppercase tracking-widest text-muted-foreground">
              Proyectos seleccionados
            </p>
            <h2 className="mt-3 font-display text-4xl font-bold tracking-tight md:text-5xl">
              Trabajo real, en vivo.
            </h2>
          </div>
          <Link
            to="/proyectos"
            className="inline-flex items-center gap-2 text-sm text-muted-foreground transition-colors hover:text-foreground"
          >
            Ver todos <ArrowRight className="size-4" />
          </Link>
        </div>
        <div className="mt-14 grid gap-x-8 gap-y-16 md:grid-cols-2">
          {projects.map((project, i) => (
            <div key={project.slug} className={i === 0 ? "md:col-span-2" : undefined}>
              <ProjectCard project={project} index={i} />
            </div>
          ))}
        </div>
      </section>

      {/* Services */}
      <section className="border-t border-border bg-card/40">
        <div className="container-page py-24 md:py-32">
          <p className="font-mono text-xs uppercase tracking-widest text-muted-foreground">Qué hacemos</p>
          <h2 className="mt-3 max-w-2xl font-display text-4xl font-bold tracking-tight md:text-5xl">
            De la idea al sitio publicado.
          </h2>
          <div className="mt-14 grid gap-px overflow-hidden rounded-xl border border-border bg-border sm:grid-cols-2 lg:grid-cols-4">
            {services.map((s, i) => (
              <div key={s.title} className="bg-background p-8 transition-colors hover:bg-card">
                <span className="font-mono text-xs text-muted-foreground">{String(i + 1).padStart(2, "0")}</span>
                <h3 className="mt-6 font-display text-xl font-semibold">{s.title}</h3>
                <p className="mt-3 text-sm leading-relaxed text-muted-foreground">{s.text}</p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* CTA */}
      <section className="container-page py-24 md:py-32">
        <div className="relative overflow-hidden rounded-3xl border border-border bg-card px-8 py-16 text-center md:py-24">
          <div className="bg-grid pointer-events-none absolute inset-0" />
          <div className="relative">
            <h2 className="text-shine mx-auto max-w-3xl font-display text-4xl font-bold tracking-tighter md:text-6xl">
              ¿Tienes un proyecto en mente?
            </h2>
            <p className="mx-auto mt-5 max-w-md text-muted-foreground">
              Cuéntanos tu idea y la convertimos en una web que se vea y funcione increíble.
            </p>
            <Button asChild variant="hero" size="xl" className="mt-10">
              <a href={WHATSAPP_URL} target="_blank" rel="noreferrer">
                Empezar ahora <ArrowRight />
              </a>
            </Button>
          </div>
        </div>
      </section>
    </>
  );
}

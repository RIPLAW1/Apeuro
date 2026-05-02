import { useState, useEffect, useRef } from "react";

// ─── QUESTION BANK ────────────────────────────────────────────────────────────
const questionBank = [
  {
    id: "euro-era1-001",
    era: 1,
    eraLabel: "1450–1648",
    unit: "Renaissance & Reformation",
    isms: ["Humanism", "Protestantism"],
    stimulus: {
      type: "text",
      source: "Martin Luther, Ninety-Five Theses, 1517 (Thesis 86)",
      content: "Why does the pope, whose wealth today is greater than the wealth of the richest Crassus, build the basilica of Saint Peter with the money of poor believers rather than with his own money?",
      authorContext: {
        socialClass: "Lower clergy / academic monk",
        politicalAffiliation: "Initially loyal to the Church; later leader of the Protestant Reformation",
        bias: "Luther was deeply frustrated with Church corruption and the sale of indulgences. His academic background made him frame grievances in theological and rational terms rather than purely emotional ones.",
      },
    },
    questions: [
      {
        question: "Luther's argument in the Ninety-Five Theses most directly challenged which aspect of the Catholic Church?",
        options: [
          "A. The Church's interpretation of Scripture as the sole source of Christian truth",
          "B. The Church's use of wealth and financial practices like the sale of indulgences",
          "C. The political authority of the Holy Roman Emperor over religious affairs",
          "D. The validity of the sacraments administered by corrupt clergy",
        ],
        answer: "B",
        explanation: "Luther directly attacks the Pope's wealth and his use of poor believers' money for the Basilica — the central grievance being financial corruption and indulgence sales, not scripture interpretation (that came later).",
        distractors: {
          A: "Scripture as the sole authority ('sola scriptura') is a later Lutheran doctrine — this specific thesis is about money and corruption, not biblical authority.",
          C: "The Holy Roman Emperor's authority is not mentioned. Luther is critiquing the Pope's financial decisions, not the political structure of the Empire.",
          D: "Sacramental validity was debated later in the Reformation. Thesis 86 is narrowly focused on the economic hypocrisy of indulgence sales.",
        },
      },
      {
        question: "Which of the following groups would most likely have used Luther's argument to advance their own political goals?",
        options: [
          "A. Spanish Inquisitors seeking to root out heresy",
          "B. German princes who resented Church taxation and papal interference",
          "C. Merchants who profited from the sale of indulgences",
          "D. Jesuits committed to the Counter-Reformation",
        ],
        answer: "B",
        explanation: "German princes had strong political and economic incentives to break from Rome — they could seize Church lands and end papal financial extractions. Luther's critique gave them theological cover for what was also a power grab.",
        distractors: {
          A: "The Inquisition actively suppressed reformers like Luther — they would have viewed his theses as dangerous heresy, not a useful argument.",
          C: "Merchants who sold indulgences profited from the very system Luther attacked. They had every reason to oppose him.",
          D: "The Jesuits were founded specifically to combat Protestant ideas — they would have defended papal authority, not exploited Luther's critique.",
        },
      },
    ],
  },
  {
    id: "euro-era2-001",
    era: 2,
    eraLabel: "1648–1815",
    unit: "Absolutism & Enlightenment",
    isms: ["Absolutism", "Enlightenment Rationalism"],
    stimulus: {
      type: "text",
      source: "Jean-Baptiste Colbert, Memorandum to Louis XIV on Finances, 1670",
      content: "Commerce is a perpetual and peaceable war of wit and energy among all nations. Each nation works incessantly to have its fair share of commerce with other countries, and to gain an advantage over them... The greatness and strength of Your Majesty are solely dependent upon his finances.",
      authorContext: {
        socialClass: "Royal minister / bureaucratic elite (bourgeois origin, not noble by birth)",
        politicalAffiliation: "Chief minister of finance under Louis XIV; architect of French Mercantilism",
        bias: "Colbert's entire career was built on maximizing royal revenue. He viewed trade as a zero-sum competition and believed state control of the economy was essential for French dominance. His perspective reflects a minister trying to justify his own policies to his king.",
      },
    },
    questions: [
      {
        question: "Colbert's description of commerce as a 'perpetual and peaceable war' most directly reflects which economic ideology?",
        options: [
          "A. Laissez-faire capitalism, as advocated by Adam Smith",
          "B. Mercantilism, emphasizing state-controlled trade and accumulation of wealth",
          "C. Physiocracy, which held that land was the source of all wealth",
          "D. Marxist theory that commerce exploits the laboring classes",
        ],
        answer: "B",
        explanation: "Colbert is the defining figure of Mercantilism — the belief that trade is a competition nations must win through state regulation, favorable balances of trade, and colonial extraction. His framing of commerce as 'war' captures the zero-sum mercantilist worldview perfectly.",
        distractors: {
          A: "Adam Smith's Wealth of Nations (1776) argued against state interference in commerce — the opposite of Colbert's position. Laissez-faire means 'let it be,' not state-directed trade wars.",
          C: "Physiocracy argued that agriculture, not trade, created wealth. Colbert is focused entirely on commerce and finance, which Physiocrats actually criticized.",
          D: "Marxist theory emerged in the 1840s, nearly 200 years after this document. Colbert has no interest in class exploitation — his concern is royal power and national revenue.",
        },
      },
    ],
  },
  {
    id: "euro-era2-002",
    era: 2,
    eraLabel: "1648–1815",
    unit: "French Revolution",
    isms: ["Republicanism", "Radicalism", "Nationalism"],
    stimulus: {
      type: "image",
      url: "https://upload.wikimedia.org/wikipedia/commons/thumb/a/a1/Jacques-Louis_David_-_Marat_assassinated_-_Google_Art_Project.jpg/800px-Jacques-Louis_David_-_Marat_assassinated_-_Google_Art_Project.jpg",
      caption: "Jacques-Louis David, The Death of Marat, 1793. Oil on canvas. Depicted moments after Marat was stabbed in his medicinal bath by Charlotte Corday.",
      authorContext: {
        socialClass: "Elite court painter turned revolutionary propagandist",
        politicalAffiliation: "Jacobin and close ally of Robespierre; used art as political propaganda",
        bias: "David was deeply invested in the Revolution's radical phase. He deliberately painted Marat in a Christ-like pose to martyr him and rally public support for the Jacobins against moderate Girondins.",
      },
    },
    questions: [
      {
        question: "David's painting of Marat's death was most likely intended to serve which purpose?",
        options: [
          "A. Document historical events accurately for future generations",
          "B. Critique the violence of the radical phase of the French Revolution",
          "C. Glorify Marat as a martyr and generate support for the Jacobin faction",
          "D. Demonstrate Neoclassical techniques to students at the Royal Academy",
        ],
        answer: "C",
        explanation: "David was a committed Jacobin who used art as propaganda. The Christ-like pose, the serene expression, and the deliberate omission of Marat's severe skin condition all serve to heroize and martyr him, rallying support for the radical Jacobin government during the Terror.",
        distractors: {
          A: "David intentionally idealized the scene — Marat's disfiguring skin disease is invisible, and his expression is peaceful rather than agonized. This is propaganda, not historical documentation.",
          B: "David fully supported the Jacobin Terror. He was not critiquing revolutionary violence; he was celebrating its victims as heroes.",
          D: "The Royal Academy was associated with the ancien régime. By 1793, David was using his art entirely for revolutionary political purposes, not academic demonstrations.",
        },
      },
    ],
  },
  {
    id: "euro-era3-001",
    era: 3,
    eraLabel: "1815–1914",
    unit: "Nationalism & Unification",
    isms: ["Nationalism", "Conservatism", "Realpolitik"],
    stimulus: {
      type: "text",
      source: "Otto von Bismarck, Speech to the Prussian Budget Committee, September 30, 1862",
      content: "The position of Prussia in Germany will not be determined by its liberalism but by its power... Prussia must concentrate its strength and hold it for the favorable moment, which has already come and gone several times. Since the treaties of Vienna, our frontiers have been ill-designed for a healthy body politic. Not through speeches and majority decisions will the great questions of the day be decided — that was the great mistake of 1848 and 1849 — but by iron and blood.",
      authorContext: {
        socialClass: "Junker (Prussian landed aristocracy)",
        politicalAffiliation: "Conservative monarchist; Minister-President of Prussia; architect of German unification from above",
        bias: "Bismarck was a pragmatic conservative who despised liberal nationalism. He deliberately used nationalist sentiment as a tool to expand Prussian power while suppressing genuine democratic movements. His 'iron and blood' is a rejection of the liberal 1848 revolutions.",
      },
    },
    questions: [
      {
        question: "Bismarck's 'iron and blood' speech most directly repudiated the methods of which earlier European movement?",
        options: [
          "A. The Congress of Vienna (1815), which sought to restore conservative monarchies",
          "B. The Revolutions of 1848, which attempted to achieve national unification through liberal parliaments",
          "C. The French Revolution's Declaration of the Rights of Man",
          "D. The Chartist Movement in Britain, which demanded working-class voting rights",
        ],
        answer: "B",
        explanation: "Bismarck explicitly names 1848 and 1849 as the 'great mistake' — when German liberals tried to unify Germany through the Frankfurt Parliament using 'speeches and majority decisions.' He is arguing that real power, not democratic deliberation, will unify Germany.",
        distractors: {
          A: "The Congress of Vienna was a conservative settlement Bismarck actually admired. He criticizes its borders ('ill-designed frontiers') but not its method — he's attacking liberalism, not conservatism.",
          C: "The Declaration of the Rights of Man is French and from 1789. Bismarck's speech is specifically about German unification debates — the 1848 Frankfurt Parliament is the clear target.",
          D: "British Chartism is a working-class British movement with no direct connection to German unification. Bismarck is not commenting on labor rights.",
        },
      },
      {
        question: "Bismarck's approach to German unification is best characterized as an example of which concept?",
        options: [
          "A. Liberal Nationalism — unification driven by popular sovereignty and constitutional government",
          "B. Realpolitik — pragmatic use of military power and diplomacy regardless of ideological principles",
          "C. Social Darwinism — belief that racial superiority justified German expansion",
          "D. Romanticism — appeal to shared cultural heritage and folk traditions to inspire unity",
        ],
        answer: "B",
        explanation: "Realpolitik is Bismarck's defining approach — cold, pragmatic, power-driven politics that ignores idealism. He used wars against Denmark, Austria, and France as calculated tools to unify Germany under Prussian dominance, not because of ideology but because of strategic interest.",
        distractors: {
          A: "Liberal Nationalism is exactly what Bismarck is rejecting. He dismisses 'speeches and majority decisions' — the tools of liberal nationalists at Frankfurt in 1848.",
          C: "Social Darwinism and racial ideology are associated with later figures. Bismarck's conservatism was about state power, not racial theory.",
          D: "Romanticism inspired cultural nationalism (Herder, Grimm brothers) but Bismarck was famously unsentimental. He used nationalism as a political tool, not a Romantic ideal.",
        },
      },
    ],
  },
  {
    id: "euro-era4-001",
    era: 4,
    eraLabel: "1914–Present",
    unit: "World Wars & Totalitarianism",
    isms: ["Totalitarianism", "Fascism", "Nationalism"],
    stimulus: {
      type: "text",
      source: "Benito Mussolini, The Doctrine of Fascism, 1932",
      content: "The foundation of Fascism is the conception of the State... For the Fascist, everything is in the State, and nothing human or spiritual exists, much less has value, outside the State. In this sense Fascism is totalitarian, and the Fascist State... interprets, develops, and potentiates the whole life of a people... The Fascist negation of socialism, democracy, liberalism should not be interpreted as a wish to push the world backwards.",
      authorContext: {
        socialClass: "Former socialist journalist turned authoritarian leader (Il Duce)",
        politicalAffiliation: "Founder of Italian Fascism; Prime Minister and dictator of Italy 1922–1943",
        bias: "Mussolini was consciously constructing an ideology to compete with both liberalism and Marxism. By 1932 he was already in power and writing this as a theoretical justification for his regime — it is explicitly self-serving political philosophy, not neutral analysis.",
      },
    },
    questions: [
      {
        question: "Mussolini's claim that 'everything is in the State' most directly contradicts which Enlightenment political tradition?",
        options: [
          "A. Absolutism, which also concentrated power in a central authority",
          "B. Liberalism, which emphasized individual rights existing prior to and above the state",
          "C. Conservatism, which valued tradition and organic social institutions",
          "D. Mercantilism, which emphasized state control of the economy",
        ],
        answer: "B",
        explanation: "Liberalism (Locke, Mill) holds that individuals possess natural rights that governments cannot violate — the individual exists before and above the state. Mussolini explicitly inverts this: the state is supreme, and nothing exists 'outside the State.' He even lists 'liberalism' as something Fascism negates.",
        distractors: {
          A: "Absolutism concentrated power in a monarch, not in an abstract 'State' as a living organism. Absolutism still had limits (divine law, natural law) that Mussolini's totalitarianism rejects entirely. The scope is different.",
          C: "Conservatism (Burke) actually valued independent institutions — church, family, local tradition — as buffers against state power. Mussolini's total state absorbs all of these.",
          D: "Mercantilism is an economic policy, not a political philosophy about individual rights. It doesn't address the relationship between the individual and the state in the way Liberalism does.",
        },
      },
    ],
  },
];

// ─── CONSTANTS ────────────────────────────────────────────────────────────────
const TIMER_SECONDS = 75;
const ERA_COLORS = {
  1: { accent: "#d97706", bg: "#78350f22", label: "Renaissance & Reformation" },
  2: { accent: "#7c3aed", bg: "#4c1d9522", label: "Absolutism & Enlightenment" },
  3: { accent: "#0891b2", bg: "#0e748022", label: "Industrialization & Nationalism" },
  4: { accent: "#dc2626", bg: "#7f1d1d22", label: "World Wars & Cold War" },
};

// ─── SMALL COMPONENTS ─────────────────────────────────────────────────────────
function IsmTag({ label }) {
  return (
    <span style={{
      display: "inline-flex", alignItems: "center", gap: 4,
      background: "#1e1b4b", border: "1px solid #4338ca",
      color: "#a5b4fc", borderRadius: 20, padding: "2px 10px",
      fontSize: 11.5, fontWeight: 600, letterSpacing: 0.4,
      fontFamily: "'DM Mono', monospace",
    }}>
      #{label}
    </span>
  );
}

function TimerArc({ seconds, total, accent }) {
  const pct = seconds / total;
  const r = 22, circ = 2 * Math.PI * r;
  const color = seconds > 30 ? accent : seconds > 15 ? "#f59e0b" : "#ef4444";
  return (
    <div style={{ position: "relative", width: 60, height: 60, flexShrink: 0 }}>
      <svg width="60" height="60" style={{ transform: "rotate(-90deg)", position: "absolute", top: 0, left: 0 }}>
        <circle cx="30" cy="30" r={r} fill="none" stroke="#ffffff0f" strokeWidth="4" />
        <circle cx="30" cy="30" r={r} fill="none" stroke={color} strokeWidth="4"
          strokeDasharray={circ} strokeDashoffset={circ * (1 - pct)}
          style={{ transition: "stroke-dashoffset 1s linear, stroke 0.4s" }}
          strokeLinecap="round" />
      </svg>
      <div style={{
        position: "absolute", inset: 0, display: "flex", flexDirection: "column",
        alignItems: "center", justifyContent: "center",
        fontFamily: "'DM Mono', monospace", fontSize: 13, fontWeight: 700, color, lineHeight: 1
      }}>{seconds}</div>
    </div>
  );
}

function SourceTooltip({ context, dark }) {
  const [open, setOpen] = useState(false);
  return (
    <div style={{ position: "relative", display: "inline-block" }}>
      <button onClick={() => setOpen(o => !o)} style={{
        background: open ? "#7c3aed" : "transparent",
        border: "1.5px solid #7c3aed", borderRadius: 8,
        color: open ? "#fff" : "#a78bfa", padding: "5px 12px",
        cursor: "pointer", fontSize: 12.5, fontWeight: 700, fontFamily: "inherit",
        transition: "all 0.18s", letterSpacing: 0.3,
      }}>🔍 Source POV</button>
      {open && (
        <div style={{
          position: "absolute", top: "calc(100% + 8px)", left: 0, zIndex: 200,
          width: 320, background: dark ? "#1e1b4b" : "#f5f3ff",
          border: "1.5px solid #7c3aed", borderRadius: 12, padding: "16px 18px",
          boxShadow: "0 20px 40px #00000060",
          animation: "fadeSlideIn 0.22s cubic-bezier(.4,0,.2,1)"
        }}>
          <div style={{ fontWeight: 700, fontSize: 12, color: "#a78bfa", marginBottom: 12, letterSpacing: 1, textTransform: "uppercase" }}>
            Author Context
          </div>
          {[
            ["🏛 Social Class", context.socialClass],
            ["⚑ Political Affiliation", context.politicalAffiliation],
            ["⚠ Bias / Limitation", context.bias],
          ].map(([label, val]) => (
            <div key={label} style={{ marginBottom: 10 }}>
              <div style={{ fontSize: 11.5, fontWeight: 700, color: "#7c3aed", marginBottom: 3 }}>{label}</div>
              <div style={{ fontSize: 13, color: dark ? "#c4b5fd" : "#374151", lineHeight: 1.55 }}>{val}</div>
            </div>
          ))}
        </div>
      )}
    </div>
  );
}

function ImageStimulus({ stimulus }) {
  const [zoomed, setZoomed] = useState(false);
  return (
    <div>
      <div style={{ position: "relative", cursor: "zoom-in", borderRadius: 10, overflow: "hidden", border: "1px solid #334155" }}
        onClick={() => setZoomed(true)}>
        <img src={stimulus.url} alt={stimulus.caption}
          style={{ width: "100%", display: "block", maxHeight: 340, objectFit: "cover" }} />
        <div style={{
          position: "absolute", bottom: 8, right: 8, background: "#000000aa",
          color: "#fff", borderRadius: 6, padding: "3px 8px", fontSize: 11, fontWeight: 600
        }}>⊕ Click to zoom</div>
      </div>
      <div style={{ fontSize: 12.5, color: "#94a3b8", fontStyle: "italic", marginTop: 10, lineHeight: 1.55 }}>
        {stimulus.caption}
      </div>
      {zoomed && (
        <div onClick={() => setZoomed(false)} style={{
          position: "fixed", inset: 0, background: "#000000ee", zIndex: 999,
          display: "flex", alignItems: "center", justifyContent: "center", cursor: "zoom-out",
          animation: "fadeSlideIn 0.2s ease"
        }}>
          <img src={stimulus.url} alt={stimulus.caption}
            style={{ maxWidth: "90vw", maxHeight: "90vh", borderRadius: 8, boxShadow: "0 0 60px #000" }} />
          <div style={{ position: "absolute", top: 20, right: 24, color: "#fff", fontSize: 28, fontWeight: 300, cursor: "pointer" }}>✕</div>
        </div>
      )}
    </div>
  );
}

function ResultsDashboard({ answers, total, onRestart, dark }) {
  const correct = answers.filter(a => a.correct).length;
  const pct = Math.round((correct / total) * 100);
  const grade = pct >= 80 ? "5" : pct >= 65 ? "4" : pct >= 50 ? "3" : "2";
  const gc = pct >= 80 ? "#34d399" : pct >= 65 ? "#60a5fa" : pct >= 50 ? "#fbbf24" : "#f87171";

  // Ism breakdown
  const ismMap = {};
  answers.forEach(a => {
    (a.isms || []).forEach(ism => {
      if (!ismMap[ism]) ismMap[ism] = { correct: 0, total: 0 };
      ismMap[ism].total++;
      if (a.correct) ismMap[ism].correct++;
    });
  });

  return (
    <div style={{
      minHeight: "100vh", background: dark ? "#0a0f1e" : "#f8fafc",
      padding: "48px 24px", fontFamily: "'Playfair Display', Georgia, serif",
      display: "flex", justifyContent: "center"
    }}>
      <div style={{ maxWidth: 700, width: "100%" }}>
        <div style={{ textAlign: "center", marginBottom: 48 }}>
          <div style={{ fontSize: 72, fontWeight: 900, color: gc, lineHeight: 1, letterSpacing: -2 }}>{pct}%</div>
          <div style={{ fontSize: 16, color: dark ? "#94a3b8" : "#64748b", marginTop: 8 }}>
            {correct}/{total} correct · Projected AP Score: <strong style={{ color: gc }}>{grade}</strong>
          </div>
          <div style={{ fontSize: 14, color: dark ? "#64748b" : "#94a3b8", marginTop: 4 }}>
            {pct >= 80 ? "🏆 Excellent work — exam-ready!" : pct >= 65 ? "📖 Review missed questions below." : "💪 Keep grinding — you've got this!"}
          </div>
        </div>

        {/* Ism Breakdown */}
        {Object.keys(ismMap).length > 0 && (
          <div style={{
            background: dark ? "#111827" : "#fff", border: `1px solid ${dark ? "#1f2937" : "#e5e7eb"}`,
            borderRadius: 16, padding: "20px 24px", marginBottom: 28
          }}>
            <div style={{ fontWeight: 700, fontSize: 13, color: "#818cf8", letterSpacing: 1.5, textTransform: "uppercase", marginBottom: 16 }}>
              Ideology Performance
            </div>
            <div style={{ display: "flex", flexWrap: "wrap", gap: 12 }}>
              {Object.entries(ismMap).map(([ism, data]) => {
                const p = Math.round((data.correct / data.total) * 100);
                const c = p === 100 ? "#34d399" : p >= 50 ? "#fbbf24" : "#f87171";
                return (
                  <div key={ism} style={{
                    background: dark ? "#1f2937" : "#f9fafb",
                    border: `1.5px solid ${c}33`, borderRadius: 10,
                    padding: "10px 16px", minWidth: 140
                  }}>
                    <div style={{ fontSize: 11.5, color: "#a5b4fc", fontFamily: "'DM Mono',monospace", marginBottom: 4 }}>#{ism}</div>
                    <div style={{ fontSize: 20, fontWeight: 800, color: c }}>{p}%</div>
                    <div style={{ fontSize: 11, color: dark ? "#6b7280" : "#9ca3af" }}>{data.correct}/{data.total} correct</div>
                  </div>
                );
              })}
            </div>
          </div>
        )}

        <div style={{ display: "flex", flexDirection: "column", gap: 14 }}>
          {answers.map((a, i) => (
            <div key={i} style={{
              background: dark ? "#111827" : "#fff",
              border: `1.5px solid ${a.correct ? "#065f46" : "#7f1d1d"}`,
              borderRadius: 13, padding: "16px 20px"
            }}>
              <div style={{ display: "flex", gap: 10, alignItems: "flex-start" }}>
                <span style={{ fontSize: 18, flexShrink: 0 }}>{a.correct ? "✅" : "❌"}</span>
                <div style={{ flex: 1 }}>
                  <div style={{ fontSize: 14, fontWeight: 600, color: dark ? "#e2e8f0" : "#1e293b", marginBottom: 6, lineHeight: 1.5 }}>
                    {a.question}
                  </div>
                  {!a.correct && (
                    <div style={{ fontSize: 13, color: "#f87171", marginBottom: 6 }}>
                      Your answer: <strong>{a.chosen?.charAt(0)}</strong> · Correct: <strong style={{ color: "#34d399" }}>{a.correctAnswer?.charAt(0)}</strong>
                    </div>
                  )}
                  <div style={{ fontSize: 13.5, color: dark ? "#94a3b8" : "#64748b", lineHeight: 1.6 }}>
                    {a.explanation}
                  </div>
                  <div style={{ display: "flex", gap: 6, flexWrap: "wrap", marginTop: 8 }}>
                    {(a.isms || []).map(ism => <IsmTag key={ism} label={ism} />)}
                  </div>
                </div>
              </div>
            </div>
          ))}
        </div>

        <div style={{ textAlign: "center", marginTop: 40 }}>
          <button onClick={onRestart} style={{
            background: "linear-gradient(135deg, #7c3aed, #4f46e5)",
            color: "#fff", border: "none", borderRadius: 12,
            padding: "14px 40px", fontSize: 16, fontWeight: 700,
            cursor: "pointer", fontFamily: "inherit", letterSpacing: 0.3,
            boxShadow: "0 8px 24px #7c3aed40"
          }}>↻ Practice Again</button>
        </div>
      </div>
    </div>
  );
}

// ─── MAIN APP ─────────────────────────────────────────────────────────────────
export default function APEuroEngine() {
  // Flatten all questions into a list with set references
  const allQuestions = [];
  questionBank.forEach(set => {
    set.questions.forEach((q, qi) => {
      allQuestions.push({ set, q, qi });
    });
  });

  const [dark, setDark] = useState(true);
  const [idx, setIdx] = useState(0);
  const [chosen, setChosen] = useState(null);
  const [timer, setTimer] = useState(TIMER_SECONDS);
  const [timesUp, setTimesUp] = useState(false);
  const [answers, setAnswers] = useState([]);
  const [finished, setFinished] = useState(false);
  const [showStudyMode, setShowStudyMode] = useState(false);
  const intervalRef = useRef(null);

  const current = allQuestions[idx];
  const { set, q } = current;
  const eraColor = ERA_COLORS[set.era];

  useEffect(() => {
    setTimer(TIMER_SECONDS);
    setTimesUp(false);
    setShowStudyMode(false);
  }, [idx]);

  useEffect(() => {
    if (chosen || timesUp) return;
    clearInterval(intervalRef.current);
    intervalRef.current = setInterval(() => {
      setTimer(t => {
        if (t <= 1) { clearInterval(intervalRef.current); setTimesUp(true); return 0; }
        return t - 1;
      });
    }, 1000);
    return () => clearInterval(intervalRef.current);
  }, [chosen, timesUp, idx]);

  const handleAnswer = (opt) => {
    if (chosen || timesUp) return;
    clearInterval(intervalRef.current);
    setChosen(opt);
    const letter = opt.charAt(0);
    setAnswers(prev => [...prev, {
      question: q.question,
      correct: letter === q.answer,
      chosen: opt,
      correctAnswer: q.options.find(o => o.startsWith(q.answer)),
      explanation: q.explanation,
      isms: set.isms,
    }]);
  };

  const handleNext = () => {
    if (idx + 1 >= allQuestions.length) { setFinished(true); return; }
    setIdx(i => i + 1);
    setChosen(null);
  };

  const handleRestart = () => {
    setIdx(0); setChosen(null); setAnswers([]);
    setFinished(false); setTimesUp(false); setShowStudyMode(false);
  };

  if (finished) {
    return <ResultsDashboard answers={answers} total={allQuestions.length} onRestart={handleRestart} dark={dark} />;
  }

  const bg = dark ? "#0a0f1e" : "#f1f5f9";
  const panel = dark ? "#111827" : "#ffffff";
  const border = dark ? "#1f2937" : "#e5e7eb";
  const text = dark ? "#e2e8f0" : "#1e293b";
  const muted = dark ? "#6b7280" : "#9ca3af";

  const optStyle = (opt) => {
    const letter = opt.charAt(0);
    const answered = chosen || timesUp;
    if (!answered) return { bg: dark ? "#111827" : "#f8fafc", border: dark ? "#1f2937" : "#e5e7eb", color: text };
    if (letter === q.answer) return { bg: "#064e3b", border: "#059669", color: "#6ee7b7" };
    if (opt === chosen) return { bg: "#450a0a", border: "#dc2626", color: "#fca5a5" };
    return { bg: dark ? "#0a0f1e" : "#f8fafc", border: dark ? "#111827" : "#e5e7eb", color: dark ? "#374151" : "#cbd5e1" };
  };

  const progress = (idx / allQuestions.length) * 100;

  return (
    <div style={{
      minHeight: "100vh", background: bg, color: text,
      fontFamily: "'Playfair Display', Georgia, serif",
      display: "flex", flexDirection: "column"
    }}>
      <style>{`
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;0,900;1,400;1,700&family=DM+Mono:wght@400;500;600&display=swap');
        * { box-sizing: border-box; margin: 0; padding: 0; }
        @keyframes fadeSlideIn { from { opacity:0; transform:translateY(10px); } to { opacity:1; transform:translateY(0); } }
        .opt-btn:not(:disabled):hover { transform: translateX(3px); opacity: 0.9; }
        .opt-btn { transition: transform 0.14s, opacity 0.14s; }
        ::-webkit-scrollbar { width: 5px; } ::-webkit-scrollbar-thumb { background: #334155; border-radius: 3px; }
      `}</style>

      {/* Header */}
      <header style={{
        display: "flex", alignItems: "center", justifyContent: "space-between",
        padding: "12px 28px", borderBottom: `1px solid ${border}`,
        background: dark ? "#0a0f1e" : "#fff", position: "sticky", top: 0, zIndex: 100,
        backdropFilter: "blur(8px)"
      }}>
        <div style={{ display: "flex", alignItems: "center", gap: 14 }}>
          <div style={{
            width: 36, height: 36, borderRadius: 10,
            background: `linear-gradient(135deg, ${eraColor.accent}, #7c3aed)`,
            display: "flex", alignItems: "center", justifyContent: "center",
            fontSize: 17, fontWeight: 900, color: "#fff", fontStyle: "italic"
          }}>E</div>
          <div>
            <div style={{ fontWeight: 700, fontSize: 16 }}>AP Euro Stimulus Engine</div>
            <div style={{ fontSize: 11, color: muted, letterSpacing: 1.2, textTransform: "uppercase", fontFamily: "'DM Mono', monospace" }}>
              Era {set.era}: {set.eraLabel} · Q{idx + 1}/{allQuestions.length}
            </div>
          </div>
        </div>
        <div style={{ display: "flex", alignItems: "center", gap: 14 }}>
          <div style={{ display: "flex", gap: 6, flexWrap: "wrap", alignItems: "center" }}>
            {set.isms.map(ism => <IsmTag key={ism} label={ism} />)}
          </div>
          <TimerArc seconds={timer} total={TIMER_SECONDS} accent={eraColor.accent} />
          <button onClick={() => setDark(d => !d)} style={{
            background: dark ? "#1f2937" : "#f1f5f9", border: `1px solid ${border}`,
            borderRadius: 8, padding: "6px 12px", cursor: "pointer", color: text,
            fontSize: 12.5, fontFamily: "inherit"
          }}>{dark ? "☀️" : "🌙"}</button>
        </div>
      </header>

      {/* Progress */}
      <div style={{ height: 3, background: dark ? "#1f2937" : "#e5e7eb" }}>
        <div style={{
          height: "100%", width: `${progress}%`,
          background: `linear-gradient(90deg, ${eraColor.accent}, #7c3aed)`,
          transition: "width 0.5s cubic-bezier(.4,0,.2,1)"
        }} />
      </div>

      {/* Era Banner */}
      <div style={{
        padding: "6px 28px", fontSize: 11.5,
        background: eraColor.bg, borderBottom: `1px solid ${eraColor.accent}22`,
        color: eraColor.accent, fontFamily: "'DM Mono', monospace",
        fontWeight: 600, letterSpacing: 0.8, display: "flex", alignItems: "center", gap: 8
      }}>
        <span>Era {set.era}</span>
        <span style={{ color: dark ? "#334155" : "#cbd5e1" }}>·</span>
        <span>{set.unit}</span>
      </div>

      {/* Main panes */}
      <div style={{ display: "flex", flex: 1, overflow: "hidden", minHeight: "calc(100vh - 100px)" }}>

        {/* LEFT: Stimulus */}
        <div style={{
          width: "44%", minWidth: 300, borderRight: `1px solid ${border}`,
          overflowY: "auto", padding: "28px 26px",
          background: dark ? "#0c1220" : "#fafafa"
        }}>
          <div style={{ display: "flex", alignItems: "center", justifyContent: "space-between", marginBottom: 16, flexWrap: "wrap", gap: 8 }}>
            <span style={{
              fontSize: 10.5, letterSpacing: 2, textTransform: "uppercase",
              fontWeight: 700, color: eraColor.accent,
              background: eraColor.bg, padding: "3px 10px", borderRadius: 6,
              fontFamily: "'DM Mono', monospace"
            }}>
              {set.stimulus.type === "image" ? "Visual Stimulus" : "Primary Source"}
            </span>
            <SourceTooltip context={set.stimulus.authorContext} dark={dark} />
          </div>

          {set.stimulus.type === "image" ? (
            <ImageStimulus stimulus={set.stimulus} />
          ) : (
            <>
              <div style={{ fontSize: 12.5, color: muted, fontStyle: "italic", marginBottom: 14, lineHeight: 1.5 }}>
                {set.stimulus.source}
              </div>
              <blockquote style={{
                borderLeft: `3px solid ${eraColor.accent}`,
                paddingLeft: 20, fontSize: 16.5, lineHeight: 1.9,
                color: text, fontStyle: "italic"
              }}>
                "{set.stimulus.content}"
              </blockquote>
            </>
          )}
        </div>

        {/* RIGHT: Questions */}
        <div style={{ flex: 1, overflowY: "auto", padding: "28px 34px" }}>
          {timesUp && !chosen && (
            <div style={{
              background: "#450a0a", border: "1.5px solid #dc2626",
              borderRadius: 10, padding: "10px 16px", marginBottom: 20,
              fontSize: 14, color: "#fca5a5", fontWeight: 600,
              animation: "fadeSlideIn 0.3s ease"
            }}>⏰ Time's up! Correct answer highlighted below.</div>
          )}

          <div style={{
            fontSize: 11, letterSpacing: 1.5, textTransform: "uppercase",
            color: muted, marginBottom: 10, fontWeight: 600, fontFamily: "'DM Mono', monospace"
          }}>Question {set.qi !== undefined ? set.qi + 1 : 1}</div>

          <div style={{ fontSize: 19.5, lineHeight: 1.75, color: text, fontWeight: 700, marginBottom: 26 }}>
            {q.question}
          </div>

          <div style={{ display: "flex", flexDirection: "column", gap: 10 }}>
            {q.options.map((opt, i) => {
              const s = optStyle(opt);
              return (
                <button key={i} className="opt-btn"
                  onClick={() => handleAnswer(opt)}
                  disabled={!!chosen || timesUp}
                  style={{
                    background: s.bg, border: `1.5px solid ${s.border}`,
                    borderRadius: 12, padding: "13px 17px", textAlign: "left",
                    cursor: chosen || timesUp ? "default" : "pointer",
                    color: s.color, fontSize: 15.5, lineHeight: 1.5,
                    fontFamily: "inherit", display: "flex", gap: 12, alignItems: "flex-start"
                  }}>
                  <span style={{
                    width: 28, height: 28, borderRadius: 7, flexShrink: 0,
                    background: s.border + "33", display: "flex", alignItems: "center",
                    justifyContent: "center", fontSize: 12, fontWeight: 700,
                    color: s.color, fontFamily: "'DM Mono', monospace", marginTop: 1
                  }}>{opt.charAt(0)}</span>
                  <span>{opt.slice(3)}</span>
                </button>
              );
            })}
          </div>

          {/* Feedback */}
          {(chosen || timesUp) && (
            <div style={{ marginTop: 26, animation: "fadeSlideIn 0.4s cubic-bezier(.4,0,.2,1)" }}>
              {/* Correct/Wrong banner */}
              <div style={{
                background: chosen?.charAt(0) === q.answer ? (dark ? "#064e3b" : "#ecfdf5") : (dark ? "#450a0a" : "#fef2f2"),
                border: `1.5px solid ${chosen?.charAt(0) === q.answer ? "#059669" : "#dc2626"}`,
                borderRadius: 13, padding: "16px 20px", marginBottom: 14
              }}>
                <div style={{ fontWeight: 700, fontSize: 14, marginBottom: 6, color: chosen?.charAt(0) === q.answer ? "#34d399" : "#f87171" }}>
                  {timesUp && !chosen ? "⏰ Time Expired" : chosen?.charAt(0) === q.answer ? "✅ Correct!" : "❌ Incorrect"}
                </div>
                <div style={{ fontSize: 14.5, lineHeight: 1.7, color: dark ? "#cbd5e1" : "#374151" }}>
                  <strong>Why this is right:</strong> {q.explanation}
                </div>
              </div>

              {/* Distractor analysis */}
              {q.distractors && (
                <div style={{
                  background: dark ? "#111827" : "#fafafa",
                  border: `1px solid ${border}`, borderRadius: 13, padding: "16px 20px", marginBottom: 14
                }}>
                  <div style={{ fontWeight: 700, fontSize: 12.5, color: "#f59e0b", marginBottom: 12, letterSpacing: 0.5, fontFamily: "'DM Mono', monospace" }}>
                    🚨 Why the wrong answers are wrong
                  </div>
                  {Object.entries(q.distractors).map(([letter, reason]) => (
                    <div key={letter} style={{ display: "flex", gap: 10, alignItems: "flex-start", marginBottom: 10 }}>
                      <span style={{
                        width: 22, height: 22, borderRadius: 5, background: "#7f1d1d",
                        color: "#fca5a5", display: "flex", alignItems: "center", justifyContent: "center",
                        fontSize: 11, fontWeight: 700, flexShrink: 0, marginTop: 2,
                        fontFamily: "'DM Mono', monospace"
                      }}>{letter}</span>
                      <span style={{ fontSize: 13.5, color: dark ? "#9ca3af" : "#64748b", lineHeight: 1.6 }}>{reason}</span>
                    </div>
                  ))}
                </div>
              )}

              {/* Study Mode: Ism breakdown */}
              <button onClick={() => setShowStudyMode(s => !s)} style={{
                background: showStudyMode ? "#1e1b4b" : "transparent",
                border: "1.5px solid #4338ca", borderRadius: 9, color: showStudyMode ? "#a5b4fc" : "#818cf8",
                padding: "7px 14px", cursor: "pointer", fontSize: 12.5, fontWeight: 700,
                fontFamily: "inherit", marginBottom: 14, transition: "all 0.18s"
              }}>
                📚 {showStudyMode ? "Hide" : "Show"} Study Mode — Ideology Breakdown
              </button>

              {showStudyMode && (
                <div style={{
                  background: dark ? "#111827" : "#f5f3ff",
                  border: "1.5px solid #4338ca", borderRadius: 13, padding: "16px 20px",
                  marginBottom: 16, animation: "fadeSlideIn 0.3s ease"
                }}>
                  <div style={{ fontWeight: 700, fontSize: 12.5, color: "#818cf8", marginBottom: 12, letterSpacing: 1, textTransform: "uppercase" }}>
                    Ideologies Tested in This Question
                  </div>
                  <div style={{ display: "flex", gap: 8, flexWrap: "wrap", marginBottom: 12 }}>
                    {set.isms.map(ism => <IsmTag key={ism} label={ism} />)}
                  </div>
                  <div style={{ fontSize: 13.5, color: dark ? "#c4b5fd" : "#4338ca", lineHeight: 1.65 }}>
                    AP Euro examiners test whether you can identify how <strong>{set.isms[0]}</strong> influenced authors, policies, and events in this period.
                    When you see these tags on future questions, ask: who benefits from this ideology? Who would oppose it?
                  </div>
                </div>
              )}

              <button onClick={handleNext} style={{
                background: `linear-gradient(135deg, ${eraColor.accent}, #7c3aed)`,
                color: "#fff", border: "none", borderRadius: 12,
                padding: "13px 32px", fontSize: 15.5, fontWeight: 700,
                cursor: "pointer", fontFamily: "inherit", letterSpacing: 0.3,
                boxShadow: `0 6px 24px ${eraColor.accent}40`
              }}>
                {idx + 1 < allQuestions.length ? "Next Question →" : "View Results →"}
              </button>
            </div>
          )}
        </div>
      </div>
    </div>
  );
}
